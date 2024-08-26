---
title: Hello World !
title-sidebar: Hello
tagline: This is my Hello World post
description: A new website is about to be forged! Therefore here is the first Hello World post, as it's supposed to be. Only for testing purposes, I extend this description with some more nonsense.

date: 1970-01-01 02:10:00
image: lmdocs-og-helloworld.jpg
categories: [Hello World, Test]
tags: [hello-world, test, bitcoin]

img_path: /assets/img/
math: true

# Is it a hidden post? exclude: true
# To-do: make work in Categories, Timeline, Further Reading
exclude: false
---


{% include tech-o-meter.html level=11 %}

This is the new introductory paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tech-o-meter.html level=11 %}


### This is my test post

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### 2<sup>nd</sup> Headline

A list

* one
* two
* three

### Code block

```javascript
console.log('test');
```

To start local Jekyll server, type in the project’s directory:
```bash
bundle exec jekyll serve --livereload --watch
```

### Math expressions

$$
\begin{flalign}

  \sum_{n=0}^{32} 210,\!000 \cdot \hspace{1.5em} \frac{50}{2^n} \hspace{1.5em} = 20,\!999,\!999.97\,690\,000
  \tag{1, super wrong}

  \\[1.35em]

  \sum_{n=0}^{32} 210,\!000 \cdot \hspace{1.5em} \frac{50}{2^n} \hspace{1.5em} = 20,\!999,\!999.99\,755\,530
  \tag{2, still wrong}
  \\[1.35em]

  \sum_{n=0}^{32} 210,\!000 \cdot  \frac{\left[\frac{50}{2^n} \cdot 10^8\right]}{10^8} = 20,\!999,\!999.97\,690\,000
  \tag{3, correct}

\end{flalign}
$$


### Tables

> **Wrong** calculation of the total amount of Bitcoin
{: .prompt-danger }

<div data-table-select="wrong-amount"></div>

| **Epoch n** | **Total Sum of BTC** | **Block Subsidy**        | **Epoch Sum of BTC** |
|------------:|---------------------:|:-------------------------|:---------------------|
| **0**       | 10,500,000           | 50                       | 10,500,000.00000000  |
| **1**       | 15,750,000           | 25                       | 5,250,000.00000000   |
| **2**       | 18,375,000           | 12.5                     | 2,625,000.00000000   |
| **3**       | 19,687,500           | 6.25                     | 1,312,500.00000000   |
| **4**       | 20,343,750           | 3.125                    | 656,250.00000000     |
| **5**       | 20,671,875           | 1.5625                   | 328,125.00000000     |
| **6**       | 20,835,937.5         | 0.78125                  | 164,062.50000000     |
| **7**       | 20,917,968.75        | 0.390625                 | 82,031.25000000      |
| **8**       | 20,958,984.375       | 0.1953125                | 41,015.62500000      |
| **9**       | 20,979,492.1875      | 0.09765625               | 20,507.81250000      |
| **10**      | 20,989,746.09375     | 0.048828125              | 10,253.90625000      |
| **11**      | 20,994,873.046875    | 0.0244140625             | 5,126.95312500       |
| **12**      | 20,997,436.5234375   | 0.01220703125            | 2,563.47656250       |
| **13**      | 20,998,718.26171870  | 0.006103515625           | 1,281.73828125       |
| **14**      | 20,999,359.13085940  | 0.0030517578125          | 640.869140625        |
| **15**      | 20,999,679.56542970  | 0.00152587890625         | 320.4345703125       |
| **16**      | 20,999,839.78271480  | 0.000762939453125        | 160.21728515625      |
| **17**      | 20,999,919.89135740  | 0.0003814697265625       | 80.108642578125      |
| **18**      | 20,999,959.94567870  | 0.00019073486328125      | 40.054321289063      |
| **19**      | 20,999,979.97283940  | 0.000095367431640625     | 20.0271606445312     |
| **20**      | 20,999,989.98641970  | 0.0000476837158203125    | 10.0135803222656     |
| **21**      | 20,999,994.99320980  | 0.00002384185791015620   | 5.00679016113281     |
| **22**      | 20,999,997.49660490  | 0.00001192092895507810   | 2.50339508056640     |
| **23**      | 20,999,998.74830250  | 0.00000596046447753906   | 1.25169754028320     |
| **24**      | 20,999,999.37415120  | 0.00000298023223876953   | 0.625848770141601    |
| **25**      | 20,999,999.68707560  | 0.000001490116119384770  | 0.312924385070801    |
| **26**      | 20,999,999.84353780  | 0.000000745058059692383  | 0.156462192535400    |
| **27**      | 20,999,999.92176890  | 0.000000372529029846191  | 0.0782310962677002   |
| **28**      | 20,999,999.96088450  | 0.000000186264514923096  | 0.0391155481338501   |
| **29**      | 20,999,999.98044220  | 0.0000000931322574615479 | 0.01955777406692500  |
| **30**      | 20,999,999.99022110  | 0.0000000465661287307739 | 0.00977888703346252  |
| **31**      | 20,999,999.99511060  | 0.0000000232830643653870 | 0.00488944351673126  |
| **32**      | 20,999,999.99755530  | 0.0000000116415321826935 | 0.00244472175836563  |
| **∑**       | <span class="wrong"></span>**20,999,999.99755530**  |



> **Correct** calculation of the total amount of Bitcoin
{: .prompt-tip }

<div data-table-select="correct-amount"></div>

| **Epoch n** | **Total Sum of BTC** | **Block Subsidy** | **Epoch Sum of BTC** |
|------------:|---------------------:|:------------------|:---------------------|
| **0**       | 10,500,000           | 50                | 10,500,000.00000000  |
| **1**       | 15,750,000           | 25                | 5,250,000.00000000   |
| **2**       | 18,375,000           | 12.5              | 2,625,000.00000000   |
| **3**       | 19,687,500           | 6.25              | 1,312,500.00000000   |
| **4**       | 20,343,750           | 3.125             | 656,250.00000000     |
| **5**       | 20,671,875           | 1.5625            | 328,125.00000000     |
| **6**       | 20,835,937.5         | 0.78125           | 164,062.50000000     |
| **7**       | 20,917,968.75        | 0.390625          | 82,031.25000000      |
| **8**       | 20,958,984.375       | 0.1953125         | 41,015.62500000      |
| **9**       | 20,979,492.1875      | 0.09765625        | 20,507.81250000      |
| **10**      | 20,989,746.09270     | 0.04882812<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 10,253.90520000      |
| **11**      | 20,994,873.045300    | 0.02441406<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 5,126.95260000       |
| **12**      | 20,997,436.5216000   | 0.01220703<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 2,563.47630000       |
| **13**      | 20,998,718.25870000  | 0.00610351<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 1,281.73710000       |
| **14**      | 20,999,359.12620000  | 0.00305175<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 640.86750000         |
| **15**      | 20,999,679.55890000  | 0.00152587<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 320.43270000         |
| **16**      | 20,999,839.77420000  | 0.00076293<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 160.21530000         |
| **17**      | 20,999,919.88080000  | 0.00038146<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 80.10660000          |
| **18**      | 20,999,959.93410000  | 0.00019073<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 40.05330000          |
| **19**      | 20,999,979.95970000  | 0.00009536<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 20.02560000          |
| **20**      | 20,999,989.97250000  | 0.00004768<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 10.01280000          |
| **21**      | 20,999,994.97890000  | 0.00002384<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 5.00640000           |
| **22**      | 20,999,997.48210000  | 0.00001192<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 2.50320000           |
| **23**      | 20,999,998.73370000  | 0.00000596<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 1.25160000           |
| **24**      | 20,999,999.35950000  | 0.00000298<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.62580000           |
| **25**      | 20,999,999.67240000  | 0.00000149<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.31290000           |
| **26**      | 20,999,999.82780000  | 0.00000074<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.15540000           |
| **27**      | 20,999,999.90550000  | 0.00000037<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.07770000           |
| **28**      | 20,999,999.94330000  | 0.00000018<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.03780000           |
| **29**      | 20,999,999.96220000  | 0.00000009<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.01890000           |
| **30**      | 20,999,999.97060000  | 0.00000004<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.00840000           |
| **31**      | 20,999,999.97480000  | 0.00000002<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.00420000           |
| **32**      | 20,999,999.97690000  | 0.00000001<span class="truncated" title="Truncated at 8th decimal digit"></span>        | 0.00210000           |
| **∑**       | <span class="correct"></span>**20,999,999.97690000**  |


## Prompts

<!-- markdownlint-capture -->
<!-- markdownlint-disable -->
> An example showing the `tip` type prompt.
{: .prompt-tip }

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `danger` type prompt.
{: .prompt-danger }
<!-- markdownlint-restore -->

### Images

![Study Bitcoin](lmdocs-og-default.jpg "Study Bitcoin"){: .w-50 .right}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.




### Tech-O-Meter

{% include tech-o-meter.html level=11 %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.








<style>







  /* Styling tables of 'wrong' and 'correct' calculations */
  /* Managing sizes of tables by going postal on hacking breakpoints */
  [data-table-select="wrong-amount"] + div.table-wrapper,
  [data-table-select="correct-amount"] + div.table-wrapper {
        max-width: 700px;
    }
  [data-table-select="wrong-amount"] + div table,
  [data-table-select="correct-amount"] + div table {
    font-size: 55%;
    line-height: 1.25;
    min-width: 100% !important;
    }
  @media (min-width: 420px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 42%;
      }
    }
  @media (min-width: 480px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 55%;
      }
    }    
  @media (min-width: 540px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 64%;
      }
    }             
  @media (min-width: 600px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 70%;
      }
    }
  @media (min-width: 850px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 55%;
      /*min-width: 100% !important;*/
      }
    }
  @media (min-width: 900px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 65%;
      /*min-width: 100% !important;*/
      }
    }    
  @media (min-width: 950px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 70%;
      }
    }
  @media (min-width: 1000px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 75%;
      }
    }
  @media (min-width: 1300px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 85%;
      }
    }
  /* Size and style of table cells  */
  [data-table-select="wrong-amount"] + div table td,
  [data-table-select="correct-amount"] + div table td {
    padding-top: 0 !important;
    padding-bottom: 0 !important;
    }
  /* Size of last row */
  [data-table-select="wrong-amount"] + div table tr:last-of-type,
  [data-table-select="correct-amount"] + div table tr:last-of-type {
    font-size:105%;
  }
  [data-table-select="wrong-amount"] + div table tr:last-of-type td,
  [data-table-select="correct-amount"] + div table tr:last-of-type td {
    padding-top: 0.3rem !important;
    padding-bottom: 0.3rem !important;
  }
  /* Table borders for wrong-amount and correct-amount */
  [data-table-select="wrong-amount"] + div table thead,
  [data-table-select="correct-amount"] + div table thead {
    border-bottom-color: var(--main-bg) !important;
    border-bottom-width: 1px;
    }
  [data-table-select="wrong-amount"] + div table tr,
  [data-table-select="correct-amount"] + div table tr {
    border-color: transparent !important;
    }

  /* Colors for 'wrong-amount' */
  [data-table-select="wrong-amount"] + div table tr,
  [data-table-select="wrong-amount"] + div table th {
    background: var(--prompt-danger-bg) !important;
    }
  [data-table-select="wrong-amount"] + div table tr:nth-child(2n+1) {
    background: rgba(255, 10, 0, 0.06) !important;
    }
  [data-table-select="wrong-amount"] + div table tbody tr:last-of-type {
    border-top-color: var(--main-bg) !important;
    border-top-width: 1px;
    }
  [data-table-select="wrong-amount"] + div table tr span.wrong:before {
    content: "\f00d";
    color: var(--prompt-danger-icon-color);
    font: var(--fa-font-solid);
    margin-right: 1ex;
    }

  /* Colors for 'correct-amount' */
  [data-table-select="correct-amount"] + div table tr,
  [data-table-select="correct-amount"] + div table th {
    background: var(--prompt-tip-bg) !important;
    }
  [data-table-select="correct-amount"] + div table tr:nth-child(2n+1) {
    background: rgba(0, 255, 25, 0.065) !important;
    }
  [data-table-select="correct-amount"] + div table tbody tr:last-of-type {
    border-top-color: var(--main-bg) !important;
    border-top-width: 1px;
    }
  [data-table-select="correct-amount"] + div table tr span.correct:before {
    content: "\f058";
    color: var(--prompt-tip-icon-color);
    font: var(--fa-font-solid);
    margin-right: 1ex;
    }
  [data-table-select="correct-amount"] + div table tr span.truncated {
    color: hsla(109, 25%, 45%, 1);
    font-weight: 300;
    font-size: 70%;
    cursor: help;
    border-left: 1px dotted hsla(109, 25%, 45%, 1);
    margin-left: 0.3ex;
    display: inline-block;
    }
  [data-table-select="correct-amount"] + div table tr span.truncated:after {
    font: var(--fa-font-solid);
    content: "\f0c4";
    color: hsla(109, 17%, 53%, 1);
    transform: scale(-1, 1) rotate(-30deg);
    display: inline-block;
    font-size: 80%;
    margin-left: 1px;
    }

</style>
