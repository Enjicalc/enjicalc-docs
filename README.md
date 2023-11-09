# Quick Start

Welcome to the Quick Start Guide for Enjicalc, your collaborative software solution to write, review, and manage engineering calculations. We know you're eager to get started with the software, so this guide will walk you through the essential steps to get you up and running quickly.

## Key App Components

Enjicalc comprises two general interfaces: a personal dashboard and a workspace. Click Create New Workspace on your dashboard page. In your workspace, click Create Sheet to start your first set of calculations. You should see a Sheet interface:

<figure><img src="images/sheet-page.png" alt="" width="563"><figcaption></figcaption></figure>

### Sheet

The Sheet represents a blueprint for your engineering calculations. It includes a header with attributes such as Sheet Title, Name of the Project, Dates, Author Name, and Checker and Approver Names. Below header starts your calculation page, which consists of two main elements: 

- Symbols
- Sections 
   
Symbols represent the fundamental part of calculations inside Enjicalc. You can compare it to a Cell in Microsoft Excel. However, Excel only stores an equation describing an engineering formula inside a cell.  Enjicalc uses a more sophisticated approach to work with engineering formulae. Enjicalc's Symbol database holds an equation, as well as crucial information related to it, including: 

- Description
- Variable Name
- Units
- Comments.

## Symbol & Mathematical Representation

In Microsoft Excel, variables inside equations represent cell location (AB302, T60), making the Excel equation very hard to review. In Enjicalc, we leveraged Mathematical Markup Language (MathML) to build and manipulate engineering formulae. Our proprietary technologies allow users to create a low-level data structure through a user-friendly interface. This data structure is then used for valuation and rendering, acting as a single source of truth. 

This architecture opens up **huge time-saving possibilities** for engineers in construction. Firstly, we are drastically accelerating the review of an individual formula. You can find an example below:

Microsoft Excel:

``` ts
=(C308 - B3 * (C309/B20) * (1 + T250/B * B20) ) / T250
```

Enjicalc:

$$
\begin{align*}
    \int_0^2
        \left(
            -\frac{1}{4}\left(e^{-4t_1}+e^{4t_1-8}\right)
        \right)
    \,dt_1
\end{align*}
$$

The fundamental goal we want to achieve with our technology is an absolute transparency.

## Symbol Editor 