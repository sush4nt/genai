# DSP Essentials

# There are four levels:

1. Advertiser
2. Campaign
3. Order
4. Line item

# Campaign Settings:

1. Campaign details
2. Schedule
3. *ID Fusion Settings*
4. *Programmatic Budget*
5. *Ad Serving Budget*
6. *Frequency Capping*
7. *Brand Safety*
8. *Conversion Attribution*
9. *Viewability*
10. *Ad Tag Type*
11. *URL Append Rules*
12. *Campaign Labels*

# Campaign Setup:

1. Campaign budget amount
2. Campaign pacing: Evenly, ASAP, Ahead

You can also set the campaign budget field to 0. This means an overall campaign budget is not applied, but **all line items** will spend their **individually** defined budgets.

For more budget flexibility, you can set this amount to be a lower number than the sum of all the RTB line item goals. But once this amount is met *all* the line items in your campaign will stop delivering. For example, if you set 100,000 EUR, all line items will spend until they reach their individual amount or until the campaign total spend reaches 100,000 EUR, whichever is first.

# Brand Controls:

Brand safety is essential to make sure your campaigns only appear in environments where the websites match your brand’s goals and vision. Providing brand safety can include preventing your ads from showing on inappropriate domains and avoiding ads appearing in unsuitable contexts on approved sites.

Ex. high Carbon Emission domains will be blocked for display ads

Toggle to switch on Brand Safety and Ad Fraud Prevention

## Viewability

**Viewable Impressions** are measured when at least 50% of the advert is viewable for at least

- One second for display ads
- Two seconds and 50% for video
- One second and 30% for large ads

Adform also fully customizable viewability thresholds for additional costs

## Frequency Capping:

**Frequency capping** is an essential tool that prevents wasting your campaign budget and annoying users, by avoiding showing the same ad to the same person.

Frequency capping can be applied on three hierarchical levels on the platform:

- Campaigns
- Orders
- Line items

## Campaign freq. capping: You can choose impression capping type and duration

1. Impression frequency capping
    - **Per Impressions** means capping the number of impressions you serve to a particular ID.
    - **Per Viewable Impressions** applies the same principle, but only for impressions that are **in view**.
2. Limit exposure time: measures and limits the total banner exposure time for each user and is ideal for branding campaigns
3. Brand Exposure Duration: multiples the Viewability time with the percentage of the user’s screen the ad covers
    1. If you were hit again with 50% of the ad showing, while you were reading an article, and it was on the screen for 14 seconds, it would be 7 seconds brand exposure duration

Let's pick a single line item, but the idea can be applied on any hierarchy level.

- The **first rule** can be set to limit the total number of impressions, which means how many times we show the banner/s to you.
- The **second rule** limits how many times you can see the banner per days/hours. For example, I want you to see the banner a total of six times, but I want it to happen over seven days. I would set up two rules - one to limit the total number of times you are shown the banner, and one to limit how many times you are shown the banner per day.
- A **third rule** could be added to differentiate between impressions and viewable impressions.

How to setup an order?

Order settings: contains Name and Schedule

Programmatic Budget: amount that works as a budget cap for the line items running under the order

**Budget Flights** A feature that lets you assign a unique budget, pacing, and daily or total goals to selected periods within the order schedule.

Forecasting and Bid Landscape

Forecasting estimates the size of your audience based on your line item settings. Any setting changes you make that affect the forecast will be updated in seconds

Bid landscape displays the estimated reach in impressions based on your bid price, and also forecasts scenarios of how a higher or a lower bid price might change this number.

Setup a line item

How to create a new line item? 

- line item settings menu has 4 main categories:
    - General: line item details, environments, banner formats, schedule
    - Inventory
    - Targeting
    - Banners

**Targeting with IAB consent** is an option that allows you to bid only on traffic that comes with a full IAB consent to use visitors' data and serve personalized ads in accordance with the GDPR Transparency and Consent Framework.
**ID fusion settings** applies ID matching for targeting purposes.

**Programmatic budget**

In Programmatic Budget, you can define the base of your budget through either money, impressions, or clicks, and set your goal. If you select to *Use Parent Level budget and pacing*, a line item will use the available RTB budget and pacing from the **order** or, if a budget was not set, from the **campaign** level.

If you want to have more control over an individual **line item**, setting the budget goal for the **line item** is the best way to do this. The **budget flights** feature allows you to plan and organize your budget for specific time frames, for example, assigning more budget for the holiday season or planning for a specific event.

You can choose from these pacing models for individual **budget flights**:

- Use **Evenly** if you want to have your spending spread equally throughout the line item period.
- Use **ASAP** if you want to spend as soon as possible. Keep in mind that this option can result in a slight overspend when targeting a large cookie pool.
- Use **Ahead** to let the system try to spend 120% of the average daily spend target each day.

Buying Strategies

Branding: driving strong brand recognition and awareness or maximizing customer engagement

1. Optimal price or Dynamic CPM
2. Bid Flat or Fixed CPM
3. Maximize Viewability Rate
4. Minimize Viewable CPM
5. Maximize VCR
6. Maximize Video Ad Impact (AVOC)

Performance: improve campaign performance such as click volume, website traffic, and conversions

1. Drive visitors to site (CPC)
2. Drive visitors and increase visit depth (CPC quality)
3. Increase sales, subscriptions or other actions (CPA)
4. Increase ROAS

Inventory sources:

Inventory contains ad spaces that you can buy. When you create a new line item, the default selects all Inventory sources

Five filters are ON by default:

1. Country
2. Environments (Web or App)
3. Banners (type: image, HTML) (format: expandable, floating)
4. Sizes
5. IAB Categories

Deal Management and Programmatic Deals:

Some deals automatically appear in deal management, including deals coming from SSPs:

1. Adform
2. Google ADX
3. DoubleClick Ad Exchange
4. Rubicon
5. Xandr SSP

Filtering and sorting deals based on:

1. Status
2. Type
3. Inventory: assigned to particular inventory
4. Advertiser: shows deals assigned to particular advertiser

Domain and App Targeting

**Add from Marketplace** function to create allow lists or block lists and discover new targeting possibilities.

Domain Block Lists, Allow Lists, and Templates

By using block lists and templates to limit bidding on domains, you can save time and make it easier to curate your media selection.

Block Lists:

1. Account level
2. Advertiser level
3. Line item level

Contextual Targeting

Contextual targeting allows you to target websites or pages associated with specific topics. If you want your ads to appear within a relevant context, contextual targeting is a great solution.

Let's look at this example:

You have selected Provider A and segments 1, 2, and 3.

You have also selected Provider B and segments 4, 5, and 6.

To target a page with this setup, it would have to match a segment from Provider A *and* a segment from Provider B, such as Provider A segment 2 *and* Provider B segment 4.

Contextual targeting is available in Inventory section

Targeting Options

Targeting is an essential step when creating a well-delivered, high performance campaign. Making sure you are hitting the right target audience will save you time and money.

Four targeting options:

1. Geo & culture:
    1. Local: countries, regions, cities, zip codes
    2. Hyperlocal
    3. Language
2. Technical
    1. Device
    2. Connection type
    3. IP range
    4. Cookie list
    5. ISP
    6. Mobile carrier
3. Retargeting
    1. Tracking point
        
        You can narrow your bidding down to a given period of time, by using the drop-down menu, and choosing between three options:
        
        - Anytime
        - During the last 'x' amount of days or hours
        - More than 'x' amount of days and hours
    2. Interacted with campaign
        
        By using the *Clicked* or *Engaged* button, you can define which interaction to target, and define the retargeting time period:
        
        - Anytime
        - During last 'x' amount of days or hours
        - More than 'x' amount of days or hours
4. DMP Audiences

Audience Marketplace

the audience tab:

1. My audiences
2. Partner audiences
3. Branded Data Providers
4. All

Banner selection

To select banners for a programmatic line item, click *Assign banners*. This will give you access to all the banners you have uploaded to the banners section of the campaign.