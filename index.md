---
layout: default
title: Home
---

<div class = 'col-2'>
    <div class = 'col'>
        <h2 class='heading'>
            <p>
                My work addresses optimization under uncertainty, market design, fairness and generative AI.
            </p>
        </h2>    
        <div class = "verbose">
            <div class='sub-navigation'>
                Software Deployment
                <p>
                    I have implemented a demo that helps you document your Python code using Generative AI.
                </p>
                <ul>
                    <li> <a class='current' href="https://codegen.criaal.com/">Python Docstring with Generative AI!</a> </li>
                </ul>
            </div>
        </div>
        <div class='verbose'>
            <div class='sub-navigation'>
            Publications:
            <p>
             </p>
            {% for item in site.data.publications %}
                <table> 
                <tbody>
                    <tr><td>Title: <a href="{{ item.link }}" class="current">
                {{ item.paper }}</a></td></tr>
                    <tr><td>Journal: 
                    {{item.state}}  
                    <i>{{ item.journal }}</i>
                    <p>
                    </p>
                    </td></tr>
                </tbody>
                </table>
            {% endfor %}
            </div>
        </div>
    </div>
    <div class ="col-3">
        <img class="img-block" alt="Carolina Riascos" src="assets/images/website_photo.jpeg">    
    </div>
</div>

