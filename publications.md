---
layout: default
title: Publications
---
<div class='heading'>
    <div class='verbose'>
    {% for item in site.data.publications %}
    <div class='sub-navigation'>
        <table>
        <tbody>
            <tr><td>Title: <a href="{{ item.link }}" class="current">
        {{ item.paper }}</a></td></tr>
            <tr><td>Journal: 
            {{item.state}}  
            <i>{{ item.journal }}</i>
            </td></tr>
            <tr class="spaceUnder"><td>Abstract: {{ item.abstract }}</td></tr>
        </tbody>
        </table>
    </div>
    {% endfor %}
    </div>
</div>