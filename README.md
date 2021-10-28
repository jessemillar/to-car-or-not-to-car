## Table of Contents
<!-- vim-markdown-toc GFM -->

* [1. Should you buy a new car?](#1-should-you-buy-a-new-car)
* [2. Finances](#2-finances)
* [3. Drivetrain](#3-drivetrain)
* [4. Subaru](#4-subaru)
* [5. Should you buy a new or used car](#5-should-you-buy-a-new-or-used-car)
* [6. What color for paint, accessories, wraps, etc.?](#6-what-color-for-paint-accessories-wraps-etc)
* [7. Should you mod your car?](#7-should-you-mod-your-car)

<!-- vim-markdown-toc -->

## 1. Should you buy a new car?
![Should you buy a new car?](1.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
carNeeds[Does your car do everything you need it to?]
    carNeeds-->|Yes| carDriving
    carNeeds-->|No| carNeedsResearch[Write a list of what you need a car to do] -->carDriving
carDriving[Does it drive how you want it to?]
    carDriving-->|Yes| carLooks
    carDriving-->|No| carDrivingResearch[Write a list of how you want your car to drive] -->carLooks
carLooks[Does it look how you want it to?]
    carLooks-->|Yes| keepCurrentCar[Keep your current car if you answered yes to all the previous questions]
    carLooks-->|No| carLooksResearch[Write a list of what you want your car to look like] -->considerNew
considerNew[Consider buying a new car if you answered no to some of the above questions]
```
</details>

## 2. Finances
![Finances](2.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
financePlan[Do you have a finance plan?]
    financePlan-->|Yes| Continue
    financePlan-->|No| noFinancePlan[Figure that out before thinking about cars]
```
</details>

## 3. Drivetrain
![Drivetrain](3.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
awd[Do you want all wheel drive?]
    awd -->|Yes| subaru[Subaru is your best bet]
    awd -->|No| noAwd[Research makes and models based on the criteria you found above]
```
</details>

## 4. Subaru
![Subaru](4.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
subaruSporty[Do you want a sportscar?]
    subaruSporty -->|Yes| subaruExpense[Expensive or cheap?]
        subaruExpense -->|Cheap| WRX
        subaruExpense -->|Expensive| STI
    subaruSporty -->|No| Crosstrek
```
</details>

## 5. Should you buy a new or used car
![New or used](5.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
willMod[Do you plan on doing mods?]
    willMod -->|Yes| voidWarrantee[Would those mods void a warrantee?]
        voidWarrantee -->|Yes| Used
        voidWarrantee -->|No| New
    willMod -->|No| New
```
</details>

## 6. What color for paint, accessories, wraps, etc.?
![Color](6.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
colorIsBoring[Is the color you're considering black, white, or red?]
    colorIsBoring -->|Yes| colorBoringAnswer[I wouldn't drive it personally]
    colorIsBoring -->|No| colorExcitingAnswer[BUY BUY BUY]
```
</details>

## 7. Should you mod your car?
![Mods](7.png)
<details>
    <summary>diagram source</summary>
    The following code block renders the above diagram using <a href="https://mermaid-js.github.io/mermaid/#/">Mermaid</a>.

```mermaid
flowchart TB
modHappy[Are you happy with your car currently?]
    modHappy-->|Yes| noMods[Don't mod your car]
    modHappy-->|No| whichMod[What are you unhappy with?]
        whichMod-->|Acceleration| newEngine[Consider an engine swap]
        whichMod-->|Handling| suspension[Consider upgrading your suspension]
        whichMod-->|Looks| whichLooks[What don't you like?]
            whichLooks-->|Rims| newRims[Consider new rims]
            whichLooks-->|Ride height| suspension
            whichLooks-->|Color| newColor[Consider a vinyl wrap]
```
</details>
