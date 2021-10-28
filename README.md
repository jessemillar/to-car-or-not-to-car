# To Car or Not to Car

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
considerNew[Consider buy a new car is you answered no to some of the above questions]
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
    financePlan-->|Yes| subDrivetrain
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
    modHappy-->|No| MOD
```
</details>
