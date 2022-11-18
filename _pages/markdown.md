---
permalink: /markdown/
title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.

2020 S. S. Arun and G. Neelakanta Iyer, "On the Analysis of COVID19 - Novel Corona Viral Disease Pandemic Spread Data Using Machine Learning Techniques," 2020 4th International Conference on Intelligent Computing and Control Systems (ICICCS), Madurai, India, 2020, pp. 1222-1227, doi: 10.1109/ICICCS48265.2020.9121027.

2020 G. N. Iyer, B. Vignesh S, B. Sohan, D. R and V. Raman, "Automated Third Umpire Decision Making in Cricket Using Machine Learning Techniques," 2020 4th International Conference on Intelligent Computing and Control Systems (ICICCS), Madurai, India, 2020, pp. 1216-1221, doi: 10.1109/ICICCS48265.2020.9121078.

2020 Dr. Ganesh Neelakanta Iyer, Vishal Raman, Aswin K. S., and Bharadwaj Veeravalli, “On the strategies for Risk Aware Cloud and Fog Broker Arbitrage Mechanisms”, in 4th International Conference on Computing Methodologies and Communication (ICCMC 2020), India, 2020.

2020 Sanjay Kumar K. K R., Goutham Subramani, Rishinathh K. S., and Dr. Ganesh Neelakanta Iyer, “ On multi-class currency classification using Convolutional Neural Networks and Cloud Computing systems for the Blind”, in Springer International Conference on Advances in Distributed Computing and Machine Learning(ICADCML-2020), VIT, Vellore, India, VIT, Vellore, India, 2020.

2020 Lakshmi Tulasi Bhavanam and Dr. Ganesh Neelakanta Iyer, “On the Classification of Kathakali Hand Gestures Using Support Vector Machines and Convolutional Neural Networks”, in International Conference on Artificial Intelligence and Signal Processing (AISP) 2020, VIT, Amaravathi, India, 2020.

2019 Dr. Ganesh Neelakanta Iyer and Kon, P. E. - Y., “B-Coop: A Novel Cooperation Enforcement Scheme for Wireless Networks”, in 26th IEEE International Conference on Telecommunications (IEEE ICT 2019), Hanoi, Vietnam, April 8-10,, Hanoi, Vietnam, April 8-10 2019, 2019.

2019 Lakshmi Tulasi Bhavanam and Dr. Ganesh Neelakanta Iyer, “On the Classification of Kathakali Hand Gestures Using Support Vector Machines and Convolutional Neural Networks”, in International Conference on Artificial Intelligence and Signal Processing (AISP) 2020, VIT, Amaravathi, India, 2020.

2018 Dr. Ganesh Neelakanta Iyer, “Evolutionary Games for Cloud, Edge and Fog Computing – A Comprehensive Study”, in 5th International Conference on Computational Intelligence in Data Mining (ICCIDM-2018), Odisha, India , 2018.

2015 Dr. Ganesh Neelakanta Iyer, Silas, S., and Iyer, G., “An optimized cloud based big data processing mechanism using Self-Organizing Map in Hadoop environments”, in 2015 International Conference on Green Computing and Internet of Things (ICGCIoT), 2015.

2014 Dr. Ganesh Neelakanta Iyer, Maddala, S., Kishore, S., and Kolamala, P. S., “WaFeR: Model-driven test-framework for testing web UI-based applications”, in ", IEEE Computer Society IT Professional Conference on Challenges in Information Systems Governance, National In-stitute of Standards and Technology (NIST) in Gaithersburg, MD, USA (IEEE ITPRO,'14), 2014

2013 Dr. Ganesh Neelakanta Iyer, Pasimuthu, J., and Loganathan, R., “PCTF: An Integrated, Extensible Cloud Test Framework for Testing Cloud Platforms and Applications”, in 2013 13th International Conference on Quality Software, 2013.

2012 Dr. Ganesh Neelakanta Iyer, Chandrasekaran, R., and Veeravalli, B., “Auction-based vs. incentive-based Multiple-Cloud orchestration mechanisms”, in 2012 IEEE International Conference on Communication, Networks and Satellite (ComNetSat), 2012.

2011 Dr. Ganesh Neelakanta Iyer and Lim, Y. Cai, “Efficient multi-channel MAC protocol and channel allocation schemes for TDMA based cognitive radio networks”, in 2011 International Conference on Communications and Signal Processing, 2011.[Abstract]

2011 Dr. Ganesh Neelakanta Iyer and Veeravalli, B., “On the resource allocation and pricing strategies in Compute Clouds using bargaining approaches”, in 2011 17th IEEE International Conference on Networks, 2011.[Abstract]
