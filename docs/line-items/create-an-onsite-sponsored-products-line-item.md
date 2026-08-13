---
title: "Create an Onsite Sponsored Products Line Item"
sidebar_position: 1
---

## Line Item Set Up

Please keep in mind: 

Once your campaign is created, the next step is to create line items that will power the campaign. 

Line items are also known as ad sets or ad groups in other DSPs. 

A line item is where you select the products and the retailer you’d like to advertise with. 

Each line item corresponds to a specific retailer and can include multiple featured SKUs, optimizations, and other relevant details. 

Line items can—and should—feature multiple products. 

To run ads across multiple retailers, you must create separate line items for each retailer. 

When building your line item strategy, consider what makes sense for your brand and which products logically align with one another. 

You can organize line items based on your KPIs. 

Since keywords are applied at the line item level, it's important to consider product relevance when grouping products. 

Campaign and Line Item Best Practices for Setup  
Use this guide to organize your Sponsored Products campaigns effectively, especially if you're managing multiple brands or product categories.Scenario 1: One Brand, One or Multiple Categories

Recommended Setup: 

Create one campaign for your brand. 

Inside the campaign, create multiple line items to segment your products based on: 

Product category (recommended) 

Price range 

1. Launch status (e.g., new vs. best-sellers)

### Why This Works?

Helps you adjust bids based on different category floor prices and competition levels. 

Makes keyword targeting easier and more relevant. 

Keeps your data organized and reporting cleaner by product type or goal. 

Tips: 

Avoid selecting the same products (SKUs) in multiple line items within the same campaign unless you're targeting different keywords in each. 

You’ll benefit from cross-line item optimization and more scale by grouping related products in the same campaign. 

### Where to view results?

Use Analytics > Campaign Summary or Activity Dashboard to check performance by line item or product category.Scenario 2: Multiple Brands, One or Multiple Categories

Recommended Setup: 

Create one campaign per brand. 

1. Add multiple line items per campaign, grouping products by:

Category 

Price point 

Product type 

Alternative Option: 

Create campaigns by Brand + Category and use line items for deeper product segmentation. 

### Why This Works?

Keeps your strategy brand focused. 

Allows you to tailor budgets, bids, and goals by both brand and product category. 

Makes it easier to compare brand performance in reports. 

### Where to view results?

Use Analytics > Campaign Summary or Activity Dashboard to view performance by brand and category. 

In this guide, you will learn how to create line items for Onsite Sponsored Products. If you’ve just completed the campaign creation workflow, you will be automatically redirected to create your first line item, or follow the steps below. 

1. Go to the Campaigns section of the platform.

Find the campaign you want to add a line item to, and click its name. 

You’ll land on the campaign page, where you can view existing line items and add new ones. 

1. Click the +Line Item button on the left side of the page.

1. Choose between the following options:

1. Set up multiple line items at once: This option is designed to make it easy to create numerous line items at once, by retailer, for some or all of the retailers that carry the products you’ve selected to promote.

1. Set up one line item at a time: Set up retailer-specific line items individually.

I’ll set them up later: Come back and create your line items later; only your campaign shell will be created.
:::warning
The I'll set them up later option is only available if you're accessing the workflow via automatic redirection immediately after creating your campaign shell.
:::

## Step 1: Settings

Naming your Line Item

The first step in creating a line item is to give it a name. The name you choose will only be visible to you on the Campaigns page and in Analytics. It will not appear in your ads and will never be visible to shoppers. 

1. Choose a name that helps you easily identify the line item within your campaign or in reports. Line item names must be unique within a campaign—each line item must have a different name.

1. Selecting a Retailer

After naming the line item, select the Retailer where you want your ads to run. 

1. Click the dropdown menu to choose from the available retailers. You can select only one retailer per line item.

The list of products available for promotion (explained later in this guide) will automatically update based on the selected retailer.
Targeting Based on Tracking Preference  
Under certain privacy laws, retailers are required to ask shoppers if they accept or refuse tracking (e.g., storing browsing information linked to their user ID). If you select a retailer that has this feature enabled, you’ll see an additional Targeting Based on Tracking Preference settings.
This setting lets you choose whether your line item should target: 

Only opted-in shoppers (default) 

Or both opted-in and opted-out shoppers 
If no targeting options are shown and you are not a Read-Only user, assume that your line item will target opted-in users only.
:::warning
No sales attribution is collected for opted-out users because attribution depends on user ID. As a result, ROAS and conversion-based KPIs may appear lower when targeting both opted-in and opted-out shoppers. However, including opted-out shoppers can increase total impressions and clicks.
:::

Bid Strategy 

In this step, you’ll choose your preferred bidding strategy. We offer Standard or Adaptive CPC optimization. Your choice in this step will impact what fields you see in Step 4: Bid

1. Setting Start and End Dates

Begin by selecting a Start Date from the calendar. Today's date is selected by default, but you may choose any future date.
:::note
If you select a future date, your line item will have a Scheduled status. It will automatically switch to Active on the selected date and begin delivering ads.
:::

Next, choose an End Date. You have two options: 

No End Date (None): Your line item will be on Active status for as long as it has funds to spend. 

Specific End Date: Select a date from the calendar. The line item will automatically stop serving ads and switch to Ended status at the end of that day.

## Multiple Line Item Set Up

1. Set up multiple line items at once instead of creating them one by one. This option will enable you to choose a common list of products to promote across various retailers, and to create multiple line items by retailer in bulk.
Each of the created line items will contain all or a subset of the products you selected, depending on each retailer’s product availability. There are two steps while setting up multiple line items at once that have been explained in detail next in this guide:  

Product Selection & Keywords  

SKU Unification & Validation of Line Items by Retailer  
You will have the option to validate which exact retailers and line items you wish to create in the second part of the workflow.

## Ad Scheduling

### How to set up an Ad Schedule?

1. Click the Ad Schedule option under the Schedule heading in Step 1 of the line item creation process.

1. Select Run Ads on a schedule to reveal a set of three dropdowns:

Day(s) of the week 

Start Time 

End Time 

To create a schedule for your Onsite Sponsored Products Line Item:

1. Choose a day of the week or use the Weekday (Monday–Friday) or Weekend (Saturday–Sunday) presets.

1. Set your desired Start Time, from 12:00 a.m. to End of Day (11:59 p.m.).

1. Set your desired End Time, from 12:00 a.m. to End of Day (11:59 p.m.).

1. Click Add to build out your schedule. You can create multiple time blocks for a single day (intraday parameters). For example, for Monday, you might schedule ads to run:

7:00–9:00 a.m. 

12:00–2:00 p.m. 

5:00 p.m.–End of Day
:::tip
Make sure your end time is after your start time for each entry.
:::

1. Ensure that you’ve selected an end time after your start time. If you set conflicting rules – for example, Monday: 9:00 a.m.-10:00 p.m., Tuesday: 6:00 a.m.-4:00 p.m., Weekdays (Monday-Friday): 7:00 a.m.-5:00 p.m., then the system will take the earliest start time available to each period and the latest possible end time:

Monday: 7:00 a.m.-10:00 p.m.  

Tuesday: 6:00 a.m.-5:00 p.m.  

Wednesday, Thursday, Friday: 7:00 a.m.-5:00 p.m.
:::warning
The scheduled times will reflect the time zone the account is set to – not your individual user settings.
:::

1. Click the x button to the right of each individual rule to remove it. To reset the schedule entirely, click Run Ads all the time.
:::note
Line items using the Ad Schedule feature will remain in Active status, including during hours of the day they are not scheduled to run.
:::

For more information on Ad Scheduling, check out the dedicated article here Ad Schedule.

## Step 1: Products

You have the option to search for your products using:

Keywords

Product IDsFinding Products by Keywords

By default, you can search by keyword using the Search Account Catalog tab. Enter a word or set of words in the search bar, and the query will return all products that match based on their names.  

Once your query is ready, click the  Search  call-to-action to retrieve the results. The results of your search appear under the Search field.

In order to select a product, click the checkbox or anywhere in the product row.
If you're having trouble finding a product, please reach out to your Criteo Team.Finding Products by Product ID

In the Multiple Line Items workflow, you can search for products using GTIN/UPC/EAN, MPN, or SKU Key as the Product ID Type.   

Copy and paste your IDs into the search field (one per line) and click on the Search call-to-action on the right-hand side. We will find and show you the exact-match products of the pasted IDs.   

1. Select the products you wish to promote. We will conduct a search for all matching products across our network of available retailers in the next step.
IMPORTANT: Please note that while initial manual product selection can be done using any of the identifiers listed above, the product unification (i.e., being able to tell that the same product selected is the same product sold on Retailer A, B, C, etc. ) is done using the GTIN/UPC/EAN value only. See Step 2 for more details.
Product Selection Best Practices:

Start broad by selecting a top-level category, then narrow with subcategories.

Check the product count indicator before saving. If below the recommendation, expand your category or add adjacent brands.

Use the category hierarchy filter to narrow by taxonomy.

Use the product count recommendation as a guide to meet or exceed the suggested number.

Sort by availability first to avoid selecting out-of-stock products.

When looking for products, it's best to avoid searching by “Product ID” unless you have a specific list of SKUs.
Keywords (optional) 
After selecting your products for cross-retailer unification, you have the option to set up positive and negative keyword targeting for all line items created after finishing the specific instance of the workflow. 

Negative Keywords
To prevent your line items from delivering on certain keywords, negate keywords at Broad and Exact match in the  Negative Keywords section below the product catalog. 

Positive Keywords 
All the products selected for inclusion in your line items will already have keywords automatically associated with them by our algorithmic keyword model. That said, if you want to manually submit additional positive Exact-match keywords, you may do so in the Submitted Keywords section. 

While manually-added positive keywords can be submitted in bulk at this step for all the line items ultimately created after finishing [this specific instance of] the workflow, manual keyword associations are always reviewed and validated at the individual line item level, per each retailer’s discretion.
Find out more about Keywords with the following articles: 

About the Commerce Max Keyword Model 

Negative Keyword Targeting  
Tips: 

1. Enter one keyword or keyword string per row.

Keywords are not case-sensitive. 

Keywords will be applied to all products targeted in the line item; therefore, to negate keywords for only certain products, create a separate line item for these products. 

Duplicate entries will be automatically de-duplicated. 

The same keyword entered in both match-type textboxes will be considered as two keywords. For example, “remote control” in the Broad Match textbox and “remote control” in the Exact Match textbox are counted as two keywords. 

Negative keywords take priority. Meaning if a keyword is in both the Negative Keyword section and the Submitted Keyword section, it will be treated as a Negated Keyword. 

Up to 1,000 Broad Match and up to 1,000 Exact Match negative keywords can be entered per line item. 

Special characters are permitted, but may automatically be parsed.
Once you’ve selected your products and made any optional adjustments to your keyword targeting, click Next.

## Budget, Caps and Pacing

1. Setting a Line Item Budget

After creating your line item, you can choose one of two budget options: 

Uncapped Budget: Select Uncapped, and your line item will spend freely from the funds available at the campaign level. The available funds are determined by the campaign budget that can be capped or uncapped. Your line item will stop spending once the Campaign budget is reached. At this point, your line item status will switch to Budget Hit. 

Capped Budget: Select Capped and enter the maximum amount for your line item to spend. Your line item might not spend the entire amount. The amount is used as a cap, and your line item will stop spending when it is reached. 

1. Setting a Line Item Pacing
After selecting a budget, you can optionally set pacing rules to control the rate at which the budget is spent. By default, no pacing is applied, and the line item will spend as quickly as possible. You can select one or a combination of the following options: 
You can optionally set line item pacing to determine how a line item spends its capped or uncapped budget. Regardless of whether a pace is set, a line item will never spend more than its set budget or campaign budget. You can set a Daily and/or Monthly Pace or an Automated Pace per line item. 

Daily Pace: Your line item won't spend more than the daily pace amount. 

Monthly Pace: Your line item costs will not exceed the monthly pace amount for each calendar month. If your line item doesn't start on the first day of the calendar month or if you update pacing throughout the month, the monthly pace will be calculated based on the remaining days in the current calendar month.   

Automated Pace: Your daily spend will be adjusted automatically. You must have a line item budget and an end date, or enter a monthly pace to select this option. 

This option is helpful if the line item does not reach its daily spend every day, but you want to make sure it has the opportunity to spend the full budget.  
You can combine a Daily and Monthly pace on a line item, but you can't combine a Daily and Automated pace on a line item. Set a Daily and/or Monthly Pace.How to set a Daily/Monthly Pace?

On the Campaigns page, click the name of the campaign that contains the line item you want to edit. 

On the Line Items page, click the Edit icon in the Daily Pace and/or Monthly Pace column and enter the amount you want to allot per day/month. 

### Click Save. How to set an Automated Pace?

On the Campaigns page, click the name of the campaign that contains the line item you want to edit. 

On the Line Items page, click the name of the line item you want to edit. 

On the Line Item Settings step, ensure that an End Date is set (in the Schedule section) and the Line Item Budget is capped (in the Line Item Budget section) or that a Monthly pace is set (in the Monthly Cap section).  

Scroll to the Daily Cap section and mark the Automated checkbox. 

1. Click Save & Exit.
Example: If your line item is set to last for 30 days and the total remaining line item budget is $30,000, then the Automated Daily Pacing option will set a pace of $1,000 delivery per day. 
Later, your same line item with a budget of $30,000 underspends over the first 10 days. There are now 20 days remaining in flight and $25,000 of budget left to spend. The Automated option will calculate that the line item needs to spend $1,250 per day in order to spend the remaining budget. With the Automated option, you don't have to adjust your daily pace every day based on yesterday's spend; the platform does it for you. 
:::warning
The automated daily pace tool will adjust your pacing every day to meet your desired spend goal based on your remaining budget.
:::

## Step 2: Line Items

SKU unification refers to the process of recognizing the same unique product across different retailers.
Example: We can tell that Brand Lipstick 123 is the same product on BeautyRetailerA and BeautyRetailerB.
Using the GTIN/EAN/UPC values of the products you’ve selected in the previous section (Product Selection & Keywords), our system will look for matching SKUs with the same identifier across all the product catalogs of the retailers in our network, in your account’s region, and under the same brand(s) associated with your account. 
Whether you search for products using GTIN, UPC, EAN, or MPN, we will always unify using the GTIN, UPC, or EAN as it is the most persistent identifier across retailers.  

When a retailer is found to sell some or all of the products you’ve selected, you will see an option to create a line item for that retailer, containing the available SKU(s), with the fields below:  

Retailer: All line items are retailer-specific.  

Line Item Name: Automatically pre-populated per this format: “[Retailer Name] – [Campaign Name] – MM/DD HR: MIN.” You can rename your line items, but they must all have unique names.  

Products: You will see the number of products found to be sold on that specific retailer out of all selected products. Clicking the fraction will show you a Product Summary page so you can review the products for your line items. If the retailer doesn’t carry all of the products you’ve selected, you can copy the GTINs that were not found.  

Start Date: It will automatically be set to the current day and cannot be set to before the current date.

End Date: Must be set to the current date or beyond, or None.  

Optimization: Choose between Clicks, Conversions, or Revenue. For more information on each option, click here.  

Line Item Bid (CPC): Defaults to the minimum value within the Suggested Bid range, which is based upon historical winning bids for products that are similar to those contained in each line item. The input CPC bid will be used as a baseline bid. With the Conversions or Revenue optimization strategy, Criteo's Commerce Max engine will slightly adjust your bid based on your ad’s likelihood to trigger a purchase, relative to your campaign performance. This means that the average CPC value you can find in your dashboards and reports will differ slightly from the entered CPC bid.

Max Bid (CPC): Applicable when using Conversions or Revenue Optimizer. It will act as a maximum hard cap for the adjusted CPC bids.  

Line Item Budget: You will have to choose between the options below, and if not set, it will be set to Uncapped by default:

Uncapped Budget: Select Uncapped, and your line item will spend freely from the funds available at the campaign level. The available funds are determined by the campaign budget and can be capped or uncapped. Your line item will stop spending once the Campaign budget is reached. At this point, your line item status will switch to Budget Hit.

Capped Budget: Select Capped and enter the maximum amount for your line item to spend. Your line item might not spend the entire amount. The amount is used as a cap, and your line item will stop spending when it is reached.

Static Daily Budget (optional): Your line item won't spend more than the static daily pace amount. If not set, it will default to None.

Static Monthly Budget (optional): Your line item costs will not exceed the monthly pace amount for each calendar month. If your line item doesn't start on the first day of the calendar month or if you update pacing throughout the month, the monthly pace will be calculated based on the remaining days in the current calendar month. If not set, it will default to None.
If you do not want to proceed with creating a line item for a certain retailer, you can uncheck the box on the left next to its name.  
For more pacing options, including automated daily pacing, edit your individual line item settings post-creation, follow the steps here.

Product Confirmation  
In order to help prevent any unwanted errors when multiple line items are created at once, we ask that you confirm that you have reviewed the products in each line item before the line items are created. See the note on the Products Column above.
Once you have checked the mandatory check box, click Create # Line Items. Your line items will be created and defaulted to Active status. The line items will behave exactly the same as any other line item created from the legacy Single-Line Item creation workflow, and you can make any adjustments freely.

## Daily Cap Overrides

Commerce Max supports two monthly and three daily (automated, fixed, none) pacing options, which apply to the line item’s entire flight and consider the line item’s total budget.  
 
The Daily Cap Override is an additional daily cap that is optional. Users can use a Daily Cap Override to set a distinct budget cap for a specific day or period within the line item’s flight. 
 
With a Daily Cap Override, you can schedule spend in advance and control exactly when and how much a line item can spend up to.How does a Daily Cap Override work?

1. Setting a Daily Cap Override is optional. Whenever it is relevant, the budget cap specified by the Daily Cap Override will supersede the budget cap set by the Daily Pace setting.
During non-applicable days, pacing will be determined by the Daily Pace amount. 
Example: Your line item is set to last between October 3rd and December 15th with a daily pace of $500. 
However, with Black Friday coming up on November 27th you want to increase your budget cap from $500 to $1,000 – on this day only though. You will therefore set up a Daily Cap Override of $1,000 for November 27th. The daily pace value will change from $500 to $1,000, on the selected day only. How to create or edit a Daily Cap Override?

To create or edit a Daily Cap Override, 

Find the line item for which you want to create or view a Daily Cap Override. 

1. Click on the edit icon in the Daily Budget column.

A pop-up should appear, showing the daily pacing settings. 

1. Click on Manage on the bottom right and access the Daily Cap Override tool. In this tool, you can see and edit the existing active or upcoming Daily Cap Overrides, as well as create new ones.

1. Click on the Add button. A new row will be added to the table where you can specify the start and end dates and the daily cap value.

To edit, click the pencil edit icon, modify the settings.

1. Click on the Tick icon to save it. Your new cap is ready and visible on the table.
You can create multiple overrides; however, they all have to be on different dates.
:::note
Daily Cap Overrides are budget caps. The line item has the opportunity to spend up to that specified amount, but might not spend the entire amount.
:::

## Monthly Cap Overrides

Commerce Max supports two monthly and three daily (automated, fixed, none) pacing options, which apply to the line item’s entire flight and consider the line item’s total budget. 
The Monthly Cap Override is an additional monthly cap that is optional. Monthly Cap Overrides can be used to adjust the budget of a single month without removing the Monthly Cap from the whole flight. Pacing will adjust for the month with the Monthly Cap Override to the new set amount.   
With a Monthly Cap Override, you can schedule monthly budget caps in advance and control exactly how much a line item can deliver up to each month.How does a Monthly Cap Override work?

1. Setting a Monthly Cap Override is optional.
A Monthly Cap Override will be respected over the default monthly cap option (Fixed, None) when applicable. During non-applicable months, the budget cap specified by the Monthly Pace setting will be used. 
Example: Your line item is set to cap at $5,000 every month using the Fixed option. Mid-flight, during a holiday month, you want to increase your cap to $10,000 for this month only. You can set up a Monthly Cap Override of $10,000 – for this month only. The monthly pace value will change from $5,000 to $10,000, for the selected month only. You can also use the override to decrease the cap.   
Monthly Cap Overrides are also used to calculate the daily needed spend for the Automated pacing option.
Example: If you are using “Automated” daily pacing and you have a Monthly Cap Override set at $10k for April 2021, the daily needed spend will be calculated off of the $10k in April 2021 – not the line item end date and total remaining budget.How to create or edit a Monthly Cap Override?

To create or edit a Monthly Cap Override: 

Find the line item for which you want to create or view a Monthly Cap Override. 

1. Click the edit icon in the Monthly Budget column.

A pop-up should appear, showing the monthly pacing settings. 

1. Click Manage on the bottom right and access the Monthly Cap Override tool. In this tool, you can see and edit the existing active or upcoming Monthly Cap Overrides, as well as create new ones.

To create a new Monthly Cap Override, click on the Add button. A new row will be added to the table where you can select the month and enter the monthly cap value.
:::note
You can create multiple overrides; however, they must be for different months.
:::

To edit a Monthly Cap Override, click the pencil edit icon on the existing override and modify the settings.

1. Click the tick icon to save it. Your new cap is ready and is visible on the table.
:::note
By default, the table will show only active or upcoming Monthly Cap Overrides, which are automatically sorted in chronological order. Monthly Cap Overrides of any status can be deleted at any point in time.
:::

:::note
Monthly Cap Overrides are budget caps. The line item has the opportunity to spend up to that specific amount, but might not spend the entire amount.
:::

## Step 2: Keyword Targeting Strategy

:::warning
This option will be available only if your retailer has enabled the Conquesting feature on their site.
In this step, you’ll choose how your line item targets keywords for your Onsite Sponsored Products line item. This helps determine when and where your ads appear on the retailer’s site, allowing you to reach the right shoppers at the right time.
:::

Keyword Types 

Generic Keywords: These are broad, non-branded search terms that describe a type of product or category,  for example: “running shoes”, “face wash”, “laptop”. They help shoppers discover products without referring to a specific brand. 

Branded Keywords: These search terms specifically include your brand name (and close variants), and they typically capture shoppers who already have strong intent for your products. They typically capture shoppers who already have a strong intent for your products. Bidding strategically on branded keywords helps you protect demand and defend visibility against competitors who may conquest your brand terms, while also letting you control which items appear - for example, prioritizing higher-margin products, best sellers, or new launches, instead of leaving placement entirely to the retailer’s organic ranking.

Conquesting Keywords: These are keywords that include a competitor’s brand or product name. You can show your ads to people who are searching for a competitor’s products. For example:  

A shopper searches: “Brand A shampoo”. 

Brand B bids on that keyword using conquesting. 

Brand B’s ad appears, potentially winning the shopper’s interest before they click on Brand A.  
:::note
In a Search environment where you can bid on both your own and competitors’ branded queries, two distinct targeting needs naturally emerge:
:::

Branded Keyword Defense

Offensive Conquesting 
Defense is about protecting and controlling your presence on searches for your brand, while offensive conquesting is about competing for visibility on competitor-branded searches to capture incremental demand.

Benefits of Conquesting Keywords

Acquire new customers (NTB growth): Reach shoppers who are currently considering a competitor and drive incremental New-to-Brand sales.

Intercept high-intent shoppers at the point of decision: Competitor-branded searches often signal strong purchase intent, giving you a chance to influence the final choice.

Grow share against priority competitors: Focus spend on specific competitor brands you want to challenge to support market share growth goals.

Increase visibility in crowded categories: When allowed by the retailer, Conquesting enables your ads to be eligible to be shown on additional high-intent searches (competitor-branded queries), increasing the inventory you can access beyond your own branded and generic keyword coverage.

Benefits of Branded Keywords

Defend against competitors conquesting you: Reduce the risk of losing high-intent shoppers to competitor ads on your branded keywords.

Control what appears on your branded searches: Prioritize which products from your portfolio show (e.g., top sellers, higher-margin items, hero SKUs, seasonal priorities) instead of leaving it entirely to the retailer’s organic ranking. It helps you -   

Keyword Targeting Options
You can choose which type of keywords your line item should target. You will find three options, and you can select the one that best matches your goals.  

Generic, Branded, and Conquesting - This strategy targets all types of keywords in a single setup: 

Generic keywords like “sneakers” or “laptops”. 

Your own branded keywords that include your brand or product name. 

Conquesting keywords that mention competitor or complementary brands. 

Generic and Branded - This option targets: 

Generic terms used for product discovery like “smartphones”, “detergent”.

Your own branded keywords that include your brand or product name.

Conquesting - This strategy focuses only on competitor or complementary brand keywords. 

It lets your ads show up when shoppers search for other known brands in your category.  

This means your product can appear when shoppers search for a competitor’s brand, capturing demand from users with strong purchase intent but who may be open to switching to your brand if shown a highly relevant alternative. 

These targeting options yield two possible line item setup approaches:Option 1: Consolidated line item (Generic, Branded, and Conquesting)

You create one line item and set the Keyword Targeting Strategy to include Generic, Branded, and Conquesting keywords together. You can use this approach if you want: 

Fewer line items to manage.

Simple and suitable for smaller or early‑stage programs.
Limitation: In practice, conquesting keywords often receive very little spend in this consolidated setup because they tend to have lower predicted CTR/CR than the defending brand on those competitor-branded queries. That can prevent conquesting from scaling. 
If you choose this option, to ensure conquesting terms can actually compete: 

Apply higher keyword bid overrides specifically on Conquesting keywords.

This “bids up” only the conquesting terms without inflating bids for Generic/Branded keywords.
:::warning
Adaptive CPC does not support keyword bid overrides. If you follow the recommended guidance and intend to implement higher bid overrides for conquesting terms, you will only be able ot use Standard Bidding. Option 2 (Recommended): Parallel Line Items
:::

Here, you create two separate line items running in parallel:

[Generic & Branded]

[Conquesting (only)]
Running two Line Items in parallel is recommended because conquesting and non-conquesting keywords serve different purposes and require different bid strategies. Separating them gives you: 

Clear control by objective: Manage budgets, bidding, and optimization independently for Generic/Branded vs Conquesting intent. 

Appropriate bidding for conquesting: Conquesting typically needs higher CPCs to compete on competitor-branded terms (where the defending brand is inherently more relevant). With a dedicated Conquesting Line Item, you can bid accordingly without affecting other keyword types. 

Simpler reporting and decision-making: Performance and learnings are easier to interpret when conquesting results aren’t blended with branded/generic activity. 

Best path when using Adaptive CPC: By setting up a dedicated Conquesting (only) line item, you can use Adaptive CPC and keep bids competitive on conquesting terms by setting a higher Max CPC at the line-item level. If you use Standard bidding instead, you can apply a higher line item CPC for the Conquesting Line Item (relative to the CPC on your (Generic & Branded Line Item) to reflect the higher bids typically needed to compete on competitor-branded keywords.  

Guidance for Generic & Branded: 

1. Set bids and budgets based on observed performance and your usual optimization approach (e.g., segmenting by keyword/category performance and adjusting over time).

For branded keywords, we recommend a defensive coverage strategy: maintain consistent sponsorship on your own brand terms to fully control which products appear to shoppers already familiar with your brand – often at relatively low CPCs when competition is limited. 

If you start seeing evidence of competitors actively conquesting your brand terms (via onsite checks or keyword-level reporting), increase bids and/or budgets on those branded keywords to preserve impression share and defend visibility 

Remember: 

Conquesting-only line item:

Use a higher line item CPC, or

With Adaptive CPC, set a higher Max CPC. 

Generic & Branded line item:

Optimize bids based on performance,

Keep branded coverage always‑on,

Increase bids/budgets when competitors target your brand.

1. Additional Keywords
You can also manually manage keywords for greater control: 

Negative Keywords - Add keywords you want to exclude to avoid showing ads on irrelevant searches. 

Submitted Keywords - Add custom keywords you'd like to target. These will be validated by the retailer and will start delivering once approved. By default, all the products selected for inclusion in your line items will already have keywords automatically associated with them by our algorithmic keyword model.
Important - We do not automatically detect when two brands have the same parent company (example - Maybelline and NYX Cosmetics under L’Oréal). If you want to avoid bidding on branded keywords of sister brands, you must manually add these keywords as negatives in the Conquesting line items. Make sure to -

1. Review keyword-level reporting regularly to identify and exclude any undesired terms.

1. Set recurring audits (bi-weekly or monthly) to monitor keyword performance.

Check the retailer site periodically to see which competitors are conquesting your brand or targeting the same competitor terms.

Use these insights to ensure defensive coverage and prioritize the most competitive keywords.
Best Practices:

1. Enter one keyword or keyword string per row.

Keywords are not case-sensitive.

Duplicate entries will be automatically de-duplicated.

The same keyword submitted in both match-type textboxes counts as two separate keywords. Example: “remote control” entered in both Broad and Exact Match fields = 2 keywords.

Negative keywords take priority. If a keyword appears in both the Submitted Keywords and Negative Keywords sections, it will be treated as Negated.

You can submit up to 1,000 Broad Match and 1,000 Exact Match negative keywords per line item.

Special characters are permitted but may be automatically parsed.

Create separate line items for each product category.
Avoid mixing unrelated categories (e.g., TVs + fridges + headphones).

Keywords (including conquesting keywords) must be relevant to all SKUs included in the line item.

If you want different keyword rules for different product types, create separate line items for those products.

Conquesting performs best with clean, competitive, single-category line items.

You should actively bid on your own branded terms to protect high-intent traffic, as competitors may target these keywords.

FAQsWhat happens if I submit a conquesting keyword for a line item with multiple categories? 

If approved, the keyword will apply to all SKUs, which may cause irrelevant targeting. To avoid this, use single‑category line items.Will a keyword be approved if it only applies to some SKUs?

No. Keywords must be relevant to every SKU in the line item.Can I use a keyword like “Bose” on a Samsung line item with both fridges and headphones? 

No. Even if it matches one category (headphones), it will be rejected.What are the risks of auto‑approved keywords?

Auto‑approved keywords aren’t category-aware. They may be matched to SKUs they shouldn’t apply to, especially in mixed-category line items. Use single‑category line items or turn off auto‑approval. 
 To learn more about Keywords, please refer to:

About the CMax Keyword Model

Negative Keyword Targeting

## Step 3: Products

You can search and select the specific products you want to promote. These products will be attributed to your line item.  
There are two ways to search for products: 

You can search by keyword using the Search Account Catalog tab 

Or you can search by Product IDs by using the Search by Product ID tab.

These two options are explained in detail below:Finding Products by Keywords 

By default, you can search by keyword using the Search Account Catalog module.  

Simply enter a word or set of words in the search bar, and the query will return all products that match based on their names. 

Once your query is ready, simply click on the Search call-to-action to retrieve the results. The results of your search appear under the Search field.  

You can narrow down your search by using the filters to find products that meet these exact specifications.  

In order to select a product, simply click the checkbox or anywhere in the product row. If you want to select all the results, click Select All Results.
If you're having trouble finding a product, please reach out to your Criteo Team. Finding Products by Product ID 

You can also search the product(s) you want to promote by using common product identifiers. Click on the Search by Product ID tab.

Then select the type of identifiers that you want to use for your search: [GTIN, UPC or EAN], MPN, Model Number, SKU ID, SKU Key, Parent ID. 

Finally, copy and paste your IDs into the search field (one per line) and click on the Search products button on the right-hand side.  

We will find and show you the exact-match products of the pasted IDs. If some IDs don’t have a match in our system, see the full details at the bottom of the search list by clicking on IDs with no matches.
If you're having trouble finding a product, please reach out to your Criteo Team. 
Product Selection Best Practices:

Start broad by selecting a top-level category, then narrow with subcategories.

Check the product count indicator before saving. If below the recommendation, expand your category or add adjacent brands.

Use the category hierarchy filter to narrow by taxonomy.

Use the product count recommendation as a guide to meet or exceed the suggested number.

Sort by availability first to avoid selecting out-of-stock products.

When looking for products, it's best to avoid searching by “Product ID” unless you have a specific list of SKUs.

## Step 4: Bid

Once you've selected your products, you'll move to setting the parameters in relation to your chosen Bid Strategy (Adaptive or Standard).
1. Setting your Line Item’s Bid (CPC)
This is the baseline amount you are willing to pay for one click of your ad, and that will enter the auction. It does not include your account fees. 
:::warning
Make sure your bid amount is above the Minimum Bid amount listed below the input field. Be careful- this minimum bid amount can change, so be sure to check back regularly to ensure your bid is above the minimum.
Depending on the optimization strategy selected (Adaptive or Standard), your CPC bid may be sensibly adjusted to drive more performance.
To set the bid:
:::

Simply enter the amount in the input field in the Bidding box. 

Commerce Max operates on a first-price auction, where all bids act independently of one another and the highest bid ultimately wins. In addition to the bid, relevancy, and prediction, decide which SKU wins the auction. Your CPC bid controls the volume that your ads will deliver.
As a reminder, there are 3 different base models that allow you to optimize your bid based on the likelihood your ad will generate a desired shopper action in line with your campaign objectives: 

1. Clicks Optimizer: This focuses on maximizing the click-through rate (CTR). The engine will adjust the delivery of your ads based on their likelihood to trigger a click.

Conversions Optimizer: This focuses on maximizing conversions. It automatically adjusts your bids based on how likely a click is to result in a conversion - such as a purchase. By focusing on conversion potential rather than just clicks, you can lower your overall cost-per-order and improve ad performance.

Revenue Optimizer: This focuses on maximizing ROAS. The Criteo Retail Media engine will adjust your bid based on your ad’s predicted attributed sales amount and the likelihood it will lead to a conversion.   
For a detailed overview of each optimization strategy and to understand how the Suggested Bids tool delivers effective recommendations, please refer to the sections below.

## Suggested Bids

Suggested Bids is an intelligent tool that provides CPC Bid recommendations for Onsite Sponsored Products line items, based on the winning bids for products that are similar to your line item’s SKUs. A suggested bid range is displayed in the Bid section (step 3) of the line item setup workflow. 

Once the line item goes live, the suggested range will also be displayed in the Edit Bid Strategy menu for each line item, where you can modify the CPC bid over the course of the flight. 

The range is based on continuous real-time analysis of historical auction data within your line item’s SKUs categories – and specifically for existing line items, the auctions your line item specifically competed in. 

Suggested Bids helps to simplify the optimization process by arming you with instant insight into competitor bids, to benchmark your own CPC against. This can help you more efficiently assess the right level at which to bid without risking overpaying relative to other advertisers in your category and ensure that your campaign starts winning auctions and reaching relevant shoppers immediately. 

If you decide impressions are worth more than the suggested bid range, you can always raise your CPC higher, and your SKUs will be more likely to win auctions and serve onsite. Conversely, you can set your bid below the range until the Minimum Bid is reached. 
:::tip
The suggested bid range can be especially helpful in determining a bid to use when you first launch your line item, given that you won’t yet have historical performance. Because the guidance is based on the most recent winning bid values that led to an ad being displayed onsite for similar products competing in your relevant categories, you can use the range to ensure your line item is competitive from the outset, while avoiding overpaying for impressions.
:::

## Adaptive CPC Optimization

:::note
:::

This model is available only for Onsite Sponsored Product campaigns.  

It requires a daily budget (static or automated) and an end date.  

You can switch back to Standard optimizers at any time by editing the campaign.  

It is not compatible with product/keyword bid overrides or page type bid multipliers.  

It is not available during multi-retailer line item setup; it is only available during single-retailer line item setup. 
### What are Adaptive CPC optimization models?
Adaptive CPC optimization is a type of bidding strategy for Sponsored Products campaigns. It represents a new generation of our Standard performance optimizers for the Sponsored Products line items. 
Like our Standard optimization models, they dynamically adjust bids based on the likelihood that showing your ad will lead to a shopper taking a desired action, as determined by your choice of base optimization model, either Clicks, Conversions, or Revenue.
However, Adaptive CPC models add an additional layer of intelligence by factoring in pacing (how quickly your line item is spending relative to its budget) and observed and predicted traffic trends on the retailer's site. This allows them to balance performance optimization with budget efficiency, ensuring your line item spends effectively across the full span of shopper activity each day.  
While Standard performance optimizers only adjust bid amounts based on performance predictions, Adaptive CPC optimizers also introduce auction throttling — the practice of participating in only a subset of available auctions when a line item is pacing ahead of its plan. This helps align both bidding and auction participation with real-time traffic and marketplace conditions. 
The goal of Adaptive CPC is to help each line item achieve strong performance outcomes while spending its full budget efficiently, avoiding premature cap-outs and maintaining visibility during peak traffic periods.
:::note
Advertisers still choose a target KPI, but only need to set a Max CPC. The optimizer handles the rest.
:::

This is an optional model, but when compared to other standard models, Adaptive is a more advanced, dynamic bidding model because it:  

It is pacing-aware and traffic-sensitive.  

Adjusts both bid value and auction participation rate based on:  

How the campaign is pacing, 

Real-time traffic patterns on the retailer’s site. 

Represents a shift from static performance optimization to more dynamic delivery optimization.

## Standard Optimization Options

The first action here in your line item creation is to select your line item’s base Optimization engine.

Let us learn in detail how each of the above models works: Clicks Optimizer

1. Select the Clicks Optimizer if you want the highest click volume relative to your impressions, or in other words, the best CTR. With this optimization strategy, the Commerce Max engine will determine which pages are most relevant to show your ad based on the shopper's current shopping behavior and their likelihood to click on your ad.
The bid will remain constant for every opportunity, and the bid you enter is the amount you will be charged for all clicks tied to the line item. 

Learning Phase 
There’s no learning phase with the Clicks Optimizer. Select, launch, go! 

CPC bid management with Clicks Optimizer 
You can adjust your CPC bids at the line item or SKU level to control the delivered volume of clicks. 
1. Additionally, we recommend that you calibrate your CPC bids based on seasonality to better control your volume of clicks.Conversions Optimizer

1. Select the Conversions Optimizer if you want to maximize your ad’s conversions and minimize your Cost-Per-Order (CPO).
The input CPC bid will be used as a baseline bid. With the conversion optimization strategy, the engine will slightly adjust your bid based on your ad’s likelihood to trigger a purchase, relative to your campaign performance. 
:::note
This means that the average CPC value you can find in your dashboards and reports will differ from the entered CPC bid.
For each line item, when using the Conversions Optimizer, you can set up a Max CPC Bid Limit (different from your input CPC bid) that will act as a maximum hard cap for the adjusted CPC bids.
:::

Learning Phase 

A learning phase starts whenever you select the Conversions Optimizer, and if your line item is live. Wait 7-14 days on average before reaching maximum efficiency. We recommend that you don’t change your line item bid settings during the learning curve. The higher volume you get, the sooner your efficiency will be reached. 

CPC bid management with Conversions Optimizer 

We recommend that you apply the same CPC bid across all your SKUs and line items. This allows the optimizer to deliver its best performance, given your available budget, and saves you time doing bid management. 
1. Additionally, we recommend that you calibrate your CPC bids based on seasonality to better control your volume of clicks.

### Can I still choose not to apply the same CPC bid across all line items?

Yes. Even though we encourage you to use the same CPC bid across all your line items, there are some scenarios where it makes sense to change it. 

Applying the same CPC bid would require you to input everywhere a CPC bid above the highest minimum bid of your line items. In that case, ultimately, if the campaign ROAS is below your ROAS target, you may reduce CPC bids on the line items or SKUs where the minimum bid allows you to do so. 

If you have hybrid objectives for your campaign (push the visibility of a specific SKU, spend volume on a particular inventory, etc.), then you should adjust the CPC bids to control the volume of scopes that matter to you. Revenue Optimizer

1. Select the Revenue Optimizer if you want to maximize your attributed revenue (ROAS). The input CPC bid will be used as a baseline bid. With the revenue optimization strategy, the Commerce Max engine will slightly adjust your bid based on your ad’s predicted attributed sales amount, relative to your campaign performance.
:::note
This means that the average CPC value you can find in your dashboards and reports will differ from the entered CPC bid.
:::

For each line item, when using the Revenue Optimizer, you can set up a Max CPC Bid Limit (different from your input CPC bid) that will act as a maximum hard cap for the adjusted CPC bids.

Learning Phase 

Note that a learning phase starts whenever you select the Revenue Optimizer, and if your line item is live. Wait 7-140 days on average before reaching maximum efficiency. We recommend that you don’t change your line item bid settings during the learning curve. The higher volume you get, the sooner your efficiency will be reached.

CPC bid management with Revenue Optimizer 

We recommend that you apply the same CPC bid across all your SKUs and line items. This allows the optimizer to deliver its best performance, given your available budget, and saves you time doing bid management. 
1. Additionally, we recommend that you calibrate your CPC bids based on seasonality to better control your volume of clicks.

### Can I still choose not to apply the same CPC bid across all line items?

Yes. Even though we encourage you to use the same CPC bid across all your line items, there are some scenarios where it makes sense to change it. 

Applying the same CPC bid would require you to input everywhere a CPC bid above the highest minimum bid of your line items. In that case, ultimately, if the campaign ROAS is below your ROAS target, you may reduce CPC bids on the line items or SKUs where the minimum bid allows you to do so. 

If you have hybrid objectives for your campaign (push the visibility of a specific SKU, spend volume on a particular inventory, etc.), then you should adjust the CPC bids to control the volume of scopes that matter to you.

## Select an Optimization Model for Onsite Sponsored Products

Before starting, please note: 
Availability: Automated optimization models are available for Action-Buy Sponsored Products campaigns. Make sure your campaign type is set accordingly.

This section walks you through choosing and applying the right optimization model for your Sponsored Products campaign. You’ll learn how Criteo’s automated bidding works, what optimizers are available, and how to configure and manage them at the line-item level. 
When setting up a Sponsored Products campaign, you'll enter a starting CPC (cost-per-click) bid. Criteo offers automated optimization models that adjust your bid in real time based on the likelihood that a shopper will take the desired action - like clicking or purchasing.

If a shopper is highly likely to act, the model may raise your bid to help you win that placement.  

If the chance is low, it may lower your bid to avoid unnecessary spend.  
This ensures your budget is used efficiently while saving you from manually adjusting bids throughout the campaign. 

You can choose one of three standard optimizers or the adaptive CPC optimizer, depending on your goals: 

1. Click Optimizer (focused on clicks)

Conversions Optimizer (focused on orders) 

Revenue Optimizer (focused on return on ad spend)

1. Click Optimizer

Optimizes for: Clickthrough Rate (CTR) 

CPC Control: Yes, your CPC bid remains fixed and will not change. 

Learning Period: No learning period required. 
Use this model if your main goal is to drive more traffic to your product pages and maintain full control over your CPC.Conversions Optimizer

Optimizes for: Cost per Order (CPO) 

CPC Control: Partial; your bid may vary slightly based on performance. To prevent overspending, you can set a maximum CPC cap. 

Learning Period: Yes, it typically takes 7–14 days to fully optimize. 
:::note
Switching to the Revenue Optimizer will restart the learning period. If you later return to the Conversions Optimizer, it will re-enter learning mode again.
Choose this if your focus is on driving purchases efficiently, and you’re okay with giving the system some flexibility in adjusting your bids. Revenue Optimizer
:::

Optimizes for: Return on Ad Spend (ROAS) 

CPC Control: Partial; your bid may fluctuate. You can set a maximum bid cap (separate from your input CPC) to limit how high the bid can go. 

Learning Period: Yes, it typically takes 7–14 days to reach peak performance.
:::note
As with the Conversions Optimizer, switching between models will restart the learning phase.
To understand how the Apative CPC Optimizer works, please refer to Adaptive CPC Optimization.
:::

:::tip
Start with Conversion or Revenue Optimizer, only if you have a sufficient volume of historical campaign data.
:::

 
Verification 
Once saved, go back to the line-item view to verify that the selected optimizer and bid settings are correctly applied. 

Common Issue 
If your campaign is not delivering, please check if your bid is too low or if the learning period is still in progress. You can reach out to your Criteo representative if you need further help.

## With Adaptive CPC, each line item:

Accelerates spend when pacing behind. 

Conserves budget when pacing ahead. 

1. Ensures smarter bidding and more efficient budget usage throughout the day.

## Optimize Your Sponsored Products Campaign

Once your campaign is live, you can start making adjustments to improve its performance. Use the guide below to optimize effectively.
:::warning
If you're using Revenue Optimizer or Conversion Optimizer, let your campaign run for at least 2 weeks before making any changes. After any adjustment, allow 7–10 days for the system to adapt.
:::

## Choose a Bidding Strategy for Sponsored Products

Your bidding strategy should match your goals, whether you're trying to get more clicks, more orders, or higher sales revenue. Below are simple tips and strategies to help you get started and adjust based on what you want to achieve.  
General Bidding Tips

Start Simple: Begin by adjusting bids at the line item level before diving into product-level changes. 

Bid Smart: We suggest starting your CPC bid at 20% above the retailer’s minimum bid (also known as the floor) to get better delivery.  

Make Small Changes: If you’re adjusting bids, increase or decrease them by no more than 10–15% at a time. Then wait 7–10 days before making further changes. 

Match Bids to Your Goal: Choose the right optimizer (Clicks, Conversions, or Revenue) based on your campaign objectives. 

Be Patient: If you're using the Conversions or Revenue optimizer, the system needs 7–10 days to learn and improve performance. 

Strategy By Goal
Understand each of the strategies by goal below:Goal: Maximize Efficiency (Get the best return for your spend) 

This is the most common strategy. It may reduce how many times your ad appears, but it helps you spend smarter. 
What to do: 

Use the Revenue optimizer (for the highest ROAS) or Conversions optimizer (for the lowest cost per order).  

1. Set a CPC cap that’s 30% higher than your bid to help the system adjust while staying in budget.

Lower CPC slightly if your cost per order is too high; raise it if you want more scale.Goal: Maximize Engagement (Get more clicks) 

This strategy is great for new products, brand awareness, and competitive categories. 
What to do: 

Use the Click optimizer. 

1. Set competitive bids to make sure your ad gets visibility.

Adjust CPC bids as needed to balance cost and performance. Goal: Maximize Sales Revenue 

You may receive fewer impressions, but this strategy can increase total sales revenue. 
What to do: 

Use the Revenue optimizer. 

1. Set strong bids to stay competitive and meet your sales goals.

Use a CPC cap (30% above your bid) to control max spend. 

1. Review top-spending products and slightly reduce bids for items with low ROAS.Goal: Maximize Units Sold

If you care more about selling more items (rather than total revenue), this is for you. 
What to do: 

Use the Conversions optimizer. 

1. Set bids to support high visibility without going below your performance targets.

Use a CPC cap that’s 30% higher than your base bid. 

At the product level, lower bids slightly for better efficiency, or raise them to scale faster. 

For more information on bidding, please check the following related articles: 

Bid Recommendations 

Sponsored Products Optimization Tips 

Keyword Bidding 

Keyword Bidding Best Practices

## Standard vs Adaptive CPC Models

Standard 
Adaptive CPC 

What it optimizes 
Bid values only, based on predicted click/conversion performance and your input CPC (+ any bid overrides or multipliers) 
Bid values and auction participation, based on pacing and retailer traffic curves 

Pacing awareness 
None - may spend too quickly or too slowly 
Yes - aligns spend rate with traffic availability 

Cap-out behavior 
Often caps early or underdelivers 
Caps later or maintains stable delivery 

Efficiency 
Risk of overspending at high CPCs early in the day, if justified by predicted performance alone 
Smarter spend distribution across the day à aims to ensure at least 16 hours of daily exposure 

Manual adjustments 
Line item-level CPC 
(Max CPC, keyword/product bid overrides, and/or page type bid multipliers) 
Max CPC only 
 
(not compatible with bid overrides or multipliers) 

Benefits for you:  

This model helps you reach traffic later in the day, which may often have higher conversion potential or be sold at more efficient rates due to lower competition. 

Aims to ensure more consistent exposure (at least 16 hours each day) 

It automatically reduces bids for line items pacing too quickly, helping maximize efficiency and value from limited budgets.  

It boosts budget utilization for line items that struggle to scale. 

It minimizes manual effort – you only need to set a Max CPC, not adjust both line item bids and product/keyword overrides and bid multipliers constantly. 

### How does it work?
:::note
We recommend setting the Max CPC to the top of the Suggested CPC range provided for Adaptive line items.
The optimizer continuously evaluates:
:::

How much should a line item have spent vs. actual spend, relative to its daily budget and proportional to current traffic volumes 

Win rates, Bidding history, Max CPC, and retailer floor prices. 
Based on this, it adjusts: 

Bid amounts (within Max CPC and floor constraints) 

Auction participation rate (how often a line item enters eligible auctions) 
This evaluation happens every few minutes, ensuring bids and pacing stay aligned with traffic and performance goals.

## Optimize by Page Type (Bid Multipliers)

### What it does?
It lets you adjust your bid depending on the type of page where your ad appears. 

Available Page Types: 

Category Page 

Home Page 

Product Detail Page 

Search Page 

AI Assistant

### How it works?

You can increase bids by up to +500% or decrease by up to -50%. 

Keep in mind: 

Your line item’s Max CPC caps the final bid. 

You cannot go below the Minimum Bid. 
Example: If base CPC is $1: 

+10% on Category Page = $1.10 

-30% on Home Page = $0.70 

### How to set a Page Type Bid Multiplier?

On the Campaigns page, click the name of the campaign you want to edit a line item for.  

On the resulting Line Items page, click the name of the desired line item.  

1. Click Placements.

1. Click the Edit icon in the Bid Multiplier column of the page type you want to adjust.

In the dialog that opens, enter the percentage you want to increase or decrease the bid by, and click Save.  

You can view the Bid Multiplier percentage and the resulting Adjusted Bid amount on the Placements page.

## Step 5: Review

The last step of creating a line item is the review of your entire line item configuration. 

After choosing your CPC bid and your optimization strategy, click on Save and Continue. 

You can now see and review all the settings you’ve selected. Once you’ve confirmed the line item is set up the way you want, click the Launch button, and the line item will be created. 

If the Start Date you’ve selected initially for your line item’s creation is today, your line item will automatically launch after you save it and switch to an Active status. 

If you’ve selected a date in the future, your line item will save and have a Scheduled status. On the selected date, it will automatically switch to Active and start delivering ads.    

At this point, your line item can be viewed by clicking on its campaign name in the Campaign Section of the UI. You can view and manage any of your line items from the Line Items page in the Campaign-specific page. 

Line Item Status 
A line item's status is determined by its configuration and by the manually controlled Off/On toggle on the Line Items page. Line items set to On or Active will spend, while line items set to Off or Inactive will not. You can adjust the status of your line items at any time. 
:::warning
If a line item is inactive for more than 90 days, the line item's status will change to Archived. Archived line items cannot be reactivated.
If you wish to reactivate an archived line item, you should copy the settings from your archived line item into a new line item and set the new line item live.
:::

## How to choose the Max CPC?

If you have an existing Open Auction Sponsored Products line item using Standard Bidding and you’re considering switching it to Adaptive CPC, we recommend first reviewing the Suggested Bid Guidance range. This range is available for all Standard bidding line items, which you’ll see when you create the line item and any time you return to edit its bid. 
:::note
The guidance can help you understand the recommended bid levels before making the switch to Adaptive CPC. When you first set your line item to Adaptive CPC, we recommend using the top value of the range as the Max CPC value.
Why should you select the maximum?
Your Max CPC is a ceiling, not the amount you will usually pay. Setting it to the upper bound gives the optimizer enough room to:
:::

Compete effectively when auctions become more competitive,

Maintain pacing when traffic or win rates fluctuate,

Prevent throttling caused by a Max CPC that’s too restrictive.
Most actual bids will still be below your Max CPC because the optimizer adjusts in real time.
### What does Max CPC actually control?
Max CPC = the highest bid the system is allowed to use when needed
Actual bids are usually lower and are determined by:

Auction competition and available traffic,

How is your line item pacing against its delivery goals.
If Max CPC is set too low, the optimizer may not be able to raise bids enough during high‑competition moments - causing missed impressions and under‑delivery, especially during peak periods.
### How is the suggested bid range calculated?
The suggested range is based on recent CPC outcomes from the most relevant auctions for your line item (past 14 days).
We calculate:

30th percentile CPC → lower bound

70th percentile CPC → upper bound
This reflects the typical CPCs required to win auctions under similar conditions.
### How does it work for new vs. existing line items?
For new line items (no history yet), we use:

The SKUs in the line item.

Their retailer taxonomy.

The inventory where the line item may serve.
Then we look at billed CPCs from clicks on that inventory over the last 14 days and compute the 30th/70th percentiles.
For existing line items (with history), we use the last 14 days of relevant auction data:

1. Click optimizer: auctions this line item actually competed in.

Revenue/Conversions optimizer: auctions from this line item plus similar line items in the same campaign using the same strategy.
We then compute the 30th/70th percentile CPC range from winning bids in those auctions.
This ensures the guidance reflects real, recent competition your line item experiences. So, set your Max CPC to the top of the suggested range to give the optimizer the flexibility it needs to deliver smoothly. Your actual CPCs will still adjust dynamically and may often be lower.
### FAQsWill I always pay the Max CPC if I choose the upper bound?

No. Max CPC is only a cap. The optimizer will bid below it most of the time based on competition and pacing.What happens if I choose the lower end of the range?

You may restrict delivery. The optimizer might not be able to bid high enough to stay competitive, especially when auction competition increases.

## Optimize by Product (Product Bid Overrides)

### What it does?
It lets you set individual CPCs for specific products.

### Why use it?

Prioritize certain products (e.g., new launches, promos). 

Fine-tune performance. 

### How it works?

Product bid overrides replace the line item CPC for that product. 

Any page type multiplier still applies on top of this override.

### How to set a product bid override?

In the Campaigns dashboard, select your desired campaign.

Once inside the campaign, click on the relevant line item.

On the Products dashboard, scroll to the Product Bid column and click the Edit icon.

1. Input the amount you want to bid for that individual product.

Alternatively, if you want to see all products that live under a campaign: 

After selecting the campaign, click on Products on the left sidebar menu of the Line Item dashboard (instead of clicking the specific line item’s hyperlinked name like you did in Step 2 above). 

You will see all products featured under the campaign, across all its line items. If you scroll to the right in this table, you will see the same Product Bid column and can also set product bid overrides here.
:::note
Make sure your input amount does not exceed the Minimum Bid amount specified in the product bid override pop-up.
:::

Editing in Bulk
To edit bids for multiple products at once:

1. Select the checkbox next to each product’s ON/OFF toggle when viewing the list of products within a specific line item, or when viewing the full product list, across all line items, within a campaign.

You can select all products by clicking the checkbox in the header row (above the Total row). If any checkbox is selected, an indicator showing how many products are currently selected will appear above the header row, along with an Edit option.  

Once all the products whose bids you wish to edit are selected, click Edit. In addition to being able to turn the products ON or OFF, you can also Edit bids.  

The bid editing functionality at the product level gives users three options by which to adjust their bids: 

By set amount  

By increasing or decreasing by % factor (e.g. if my bid is $1 and I increase by +20%, my new bid will be $1.20)  

By removing any product bid overrides 
If a line item has a Max Bid set and you wish to increase your product bid overrides to a set amount or by a percentage factor that would result in new override bids which exceed the current Max CPC value, choosing the Increase Maximum Bid option allows the line item’s Max CPC bid to be updated simultaneously to match either the new amount (if by set amount), or the highest resulting bid value of the set of bids which have been changed by percentage factor.  
If this option is not selected, the product bids’ increases will be capped such that the new bids will match the existing Max CPC value of their respective line item.  
Lastly, if the proposed increases do not result in a new product bid override amounts that exceed the line item’s current Max CPC value, selecting this option has no impact.  

Existing  
Product Bid Override(s) 
Existing Max CPC 
Proposed Increase 
Increase Maximum Bid Option Selected 
Resulting Product Bid(s) Override(s) 
Resulting Max Bid 

Product A Bid: $1 
 
Product B Bid: $1.50  
$2 
Increase by +110% 
Yes 
Product A Bid: $1 + ($1*110%) = $2.10 
 
Product B Bid: $1.50 + ($1.50*110%) = $3.15 
$2 → $3.15 

Product A Bid: $1 
 
Product B Bid: $1.50 
$2 
By Set Amount to $2.10 
No 
Product A Bid: $1 → $2 
 
Product B Bid: $1.50 → $2 
 
The increasewill be capped to the existing Max CPC value of $2. 
$2 
No change. 

Product A Bid: $1 
 
Product B Bid: $1.50 
$2 
Increase by +20% 
Yes 
Product A Bid: $1 + ($1*20%) = $1.20 
 
Product B Bid: $1.50 + ($1.50*20%) = $1.80 
$2 
No change, since $1.80 < $2.  
You will see a column showing the Original and New Bids to review your changes before clicking Save.  
:::warning
Final bid cannot exceed Max CPC or go below Minimum Bid.
:::

## Understanding the Cap Out Report

Adaptive CPC is designed to reduce early budget cap outs by pacing spend throughout the day. However, missed opportunities can still occur if a line item participates in fewer auctions, especially during high-traffic periods. 

### What is Missed Traffic %?
Missed Traffic % measures how often a line item didn’t compete in auctions during its scheduled active hours. It’s calculated based on the percentage of page loads where the line item was not active, and each inactive period is weighed by the amount of traffic during that time. 
Missed Traffic % = Number of page loads where the advertiser didn't display an impression after capping out or due to lowered participation rate / Total number of page loads in the day 
### How do scheduled hours affect the calculation?

If no dayparting is applied, the line item is considered live for all 24 hours. 

If dayparting is applied, only the scheduled active hours are included in the calculation.

## Optimize by Keyword

### What it does?
It sets bids per keyword (auto-generated or manual). 

### How to use it?

Increase bids for high-performing keywords. 

1. Add/exclude keywords to fine-tune targeting.

## Bidding Hierarchy

Now that you've explored the different bidding tools available, it's important to understand how bidding decisions are prioritized within the platform. This hierarchy determines which bid amount is used when your ads enter an auction.
1. Line Item CPC Bid
When you set up a line item, you define a Cost-Per-Click (CPC) bid. This is the default bid the platform uses unless a more specific override is applied.
2. Product-Level Bid
If you assign a product bid, it overrides the line item CPC bid for that specific product. This allows for more granular control over bidding at the product level.
3. Page Type Bid Multipliers
If you've configured bid multipliers for specific page types:

The multiplier applies to the product bid if one is set.

If no product bid is set, the multiplier applies to the line item CPC bid.

If no product bid is set, the platform uses the line item CPC bid, adjusted by any applicable page type multiplier.

If a product bid is set, the platform uses the product bid, adjusted by the page type multiplier.
This hierarchy ensures that your bidding strategy reflects both broad campaign goals and specific product-level priorities.
