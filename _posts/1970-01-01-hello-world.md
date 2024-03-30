---
title: Hello World !
tagline: This is my Hello World post
description: A new website is about to be forged! Therefore here is the first Hello World post, as it's supposed to be. Only for testing purposes, I extend this description with some more nonsense.

image: og-hello-world.jpg
date: 1970-01-01 02:10:00
categories: [Hello World, Bitcoin, Test]
tags: [hello-world, test, bitcoin]
img_path: /assets/img/
math: true
exclude: false
---


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

| **Epoch n** | **Block Subsidy**        | **Blocks** | **Epoch Sum of BTC** | **Total Sum of BTC** |
|------------:|-------------------------:|-----------:|---------------------:|---------------------:|
| **0**       | 50                       | 210,000    | 10,500,000.00000000  | 10,500,000           |
| **1**       | 25                       | 210,000    | 5,250,000.00000000   | 15,750,000           |
| **2**       | 12.5                     | 210,000    | 2,625,000.00000000   | 18,375,000           |
| **3**       | 6.25                     | 210,000    | 1,312,500.00000000   | 19,687,500           |
| **4**       | 3.125                    | 210,000    | 656,250.00000000     | 20,343,750           |
| **5**       | 1.5625                   | 210,000    | 328,125.00000000     | 20,671,875           |
| **6**       | 0.78125                  | 210,000    | 164,062.50000000     | 20,835,937.5         |
| **7**       | 0.390625                 | 210,000    | 82,031.25000000      | 20,917,968.75        |
| **8**       | 0.1953125                | 210,000    | 41,015.62500000      | 20,958,984.375       |
| **9**       | 0.09765625               | 210,000    | 20,507.81250000      | 20,979,492.1875      |
| **10**      | 0.048828125              | 210,000    | 10,253.90625000      | 20,989,746.09375     |
| **11**      | 0.0244140625             | 210,000    | 5,126.95312500       | 20,994,873.046875    |
| **12**      | 0.01220703125            | 210,000    | 2,563.47656250       | 20,997,436.5234375   |
| **13**      | 0.006103515625           | 210,000    | 1,281.73828125       | 20,998,718.26171870  |
| **14**      | 0.0030517578125          | 210,000    | 640.869140625        | 20,999,359.13085940  |
| **15**      | 0.00152587890625         | 210,000    | 320.4345703125       | 20,999,679.56542970  |
| **16**      | 0.000762939453125        | 210,000    | 160.21728515625      | 20,999,839.78271480  |
| **17**      | 0.0003814697265625       | 210,000    | 80.108642578125      | 20,999,919.89135740  |
| **18**      | 0.00019073486328125      | 210,000    | 40.054321289063      | 20,999,959.94567870  |
| **19**      | 0.000095367431640625     | 210,000    | 20.0271606445312     | 20,999,979.97283940  |
| **20**      | 0.0000476837158203125    | 210,000    | 10.0135803222656     | 20,999,989.98641970  |
| **21**      | 0.00002384185791015620   | 210,000    | 5.00679016113281     | 20,999,994.99320980  |
| **22**      | 0.00001192092895507810   | 210,000    | 2.50339508056640     | 20,999,997.49660490  |
| **23**      | 0.00000596046447753906   | 210,000    | 1.25169754028320     | 20,999,998.74830250  |
| **24**      | 0.00000298023223876953   | 210,000    | 0.625848770141601    | 20,999,999.37415120  |
| **25**      | 0.000001490116119384770  | 210,000    | 0.312924385070801    | 20,999,999.68707560  |
| **26**      | 0.000000745058059692383  | 210,000    | 0.156462192535400    | 20,999,999.84353780  |
| **27**      | 0.000000372529029846191  | 210,000    | 0.0782310962677002   | 20,999,999.92176890  |
| **28**      | 0.000000186264514923096  | 210,000    | 0.0391155481338501   | 20,999,999.96088450  |
| **29**      | 0.0000000931322574615479 | 210,000    | 0.01955777406692500  | 20,999,999.98044220  |
| **30**      | 0.0000000465661287307739 | 210,000    | 0.00977888703346252  | 20,999,999.99022110  |
| **31**      | 0.0000000232830643653870 | 210,000    | 0.00488944351673126  | 20,999,999.99511060  |
| **32**      | 0.0000000116415321826935 | 210,000    | 0.00244472175836563  | 20,999,999.99755530  |
| **∑**       |                          | **6,930,000**  |                  | <span></span>**20,999,999.99755530**  |


> **Correct** calculation of the total amount of Bitcoin
{: .prompt-tip }

<div data-table-select="correct-amount"></div>

| **Epoch n** | **Block Subsidy** | **Blocks** | **Epoch Sum of BTC** | **Total Sum of BTC** |
|------------:|------------------:|-----------:|---------------------:|---------------------:|
| **0**       | 50                | 210,000    | 10,500,000.00000000  | 10,500,000           |
| **1**       | 25                | 210,000    | 5,250,000.00000000   | 15,750,000           |
| **2**       | 12.5              | 210,000    | 2,625,000.00000000   | 18,375,000           |
| **3**       | 6.25              | 210,000    | 1,312,500.00000000   | 19,687,500           |
| **4**       | 3.125             | 210,000    | 656,250.00000000     | 20,343,750           |
| **5**       | 1.5625            | 210,000    | 328,125.00000000     | 20,671,875           |
| **6**       | 0.78125           | 210,000    | 164,062.50000000     | 20,835,937.5         |
| **7**       | 0.390625          | 210,000    | 82,031.25000000      | 20,917,968.75        |
| **8**       | 0.1953125         | 210,000    | 41,015.62500000      | 20,958,984.375       |
| **9**       | 0.09765625        | 210,000    | 20,507.81250000      | 20,979,492.1875      |
| **10**      | 0.04882812        | 210,000    | 10,253.90520000      | 20,989,746.09270     |
| **11**      | 0.02441406        | 210,000    | 5,126.95260000       | 20,994,873.045300    |
| **12**      | 0.01220703        | 210,000    | 2,563.47630000       | 20,997,436.5216000   |
| **13**      | 0.00610351        | 210,000    | 1,281.73710000       | 20,998,718.25870000  |
| **14**      | 0.00305175        | 210,000    | 640.86750000         | 20,999,359.12620000  |
| **15**      | 0.00152587        | 210,000    | 320.43270000         | 20,999,679.55890000  |
| **16**      | 0.00076293        | 210,000    | 160.21530000         | 20,999,839.77420000  |
| **17**      | 0.00038146        | 210,000    | 80.10660000          | 20,999,919.88080000  |
| **18**      | 0.00019073        | 210,000    | 40.05330000          | 20,999,959.93410000  |
| **19**      | 0.00009536        | 210,000    | 20.02560000          | 20,999,979.95970000  |
| **20**      | 0.00004768        | 210,000    | 10.01280000          | 20,999,989.97250000  |
| **21**      | 0.00002384        | 210,000    | 5.00640000           | 20,999,994.97890000  |
| **22**      | 0.00001192        | 210,000    | 2.50320000           | 20,999,997.48210000  |
| **23**      | 0.00000596        | 210,000    | 1.25160000           | 20,999,998.73370000  |
| **24**      | 0.00000298        | 210,000    | 0.62580000           | 20,999,999.35950000  |
| **25**      | 0.00000149        | 210,000    | 0.31290000           | 20,999,999.67240000  |
| **26**      | 0.00000074        | 210,000    | 0.15540000           | 20,999,999.82780000  |
| **27**      | 0.00000037        | 210,000    | 0.07770000           | 20,999,999.90550000  |
| **28**      | 0.00000018        | 210,000    | 0.03780000           | 20,999,999.94330000  |
| **29**      | 0.00000009        | 210,000    | 0.01890000           | 20,999,999.96220000  |
| **30**      | 0.00000004        | 210,000    | 0.00840000           | 20,999,999.97060000  |
| **31**      | 0.00000002        | 210,000    | 0.00420000           | 20,999,999.97480000  |
| **32**      | 0.00000001        | 210,000    | 0.00210000           | 20,999,999.97690000  |
| **∑**       |                   | **6,930,000**  |                  | <span></span>**20,999,999.97690000**  |



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

![Study Bitcoin](og-default.jpg "Study Bitcoin")Study Bitcoin







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
      font-size: 35%;
      }
    }
  @media (min-width: 460px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 40%;
      }
    }    
  @media (min-width: 500px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 45%;
      }
    }
  @media (min-width: 550px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 55%;
      }
    }             
  @media (min-width: 600px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 60%;
      }
    }
  @media (min-width: 600px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 60%;
      }
    }
  @media (min-width: 700px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 75%;
      }
    }
  @media (min-width: 850px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 60%;
      /*min-width: 100% !important;*/
      }
    }
  @media (min-width: 1000px) {
    [data-table-select="wrong-amount"] + div table,
    [data-table-select="correct-amount"] + div table {
      font-size: 70%;
      }
    }
  @media (min-width: 1200px) {
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
  [data-table-select="wrong-amount"] + div table tr span:before {
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
  [data-table-select="correct-amount"] + div table tr span:before {
    content: "\f058";
    color: var(--prompt-tip-icon-color);
    font: var(--fa-font-solid);
    margin-right: 1ex;
  }


</style>
