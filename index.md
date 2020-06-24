---
title: MSBA NTU
---

We’ll teach you how to master basics of python and data analytics. We will be focusing on
Numpy, Pandas and Sklearn. Knowing these tools and libraries not only enables you to spend less time
on figuring out how to wrangle your datasets, but it also lets you solve problems that seems
impossible to do with a spreadsheet 

# Feedback
For feedback on the sessions  [feeback form](https://forms.gle/dewTPgD13zDhucjj8).

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

# About the class

 - **Staff**: This class is taught by [Teoh Teik Toe](mailto:ttteoh@ntu.edu.sg)
 - **Questions**: Email us. :)

# External Resources 
 - [YouTube](....) .



If you are interested to do a translation of our cite / material
[Email](mailto:ttteoh@ntu.edu.sg)
[pull request](https://github.com/NTUMSBA/MSBA-public-2020/pulls) so
we can add it to the list!


---
<div class="small center">
<p><a href="https://github.com/NTUMSBA/MSBA-public-2020">Source code</a>.</p>
</div>