# Advanced Google Analytics

[Intro](https://analytics.google.com/analytics/academy/course/7) 1:31

1. Data collection and Processing
  1. [Google Analytics data collection](https://analytics.google.com/analytics/academy/course/7/unit/1/lesson/1) 5:39
The GA tracking code drop a cookie into users browserfor tbe website and any subdomain

  1. Categorizing into users and sessions 6:06

  1. Applying configuration settings 5:12  
  >  There are four types of Goals in Google Analytics:
  > 1. Destination
  > 1. Event Goals
  > 1. Duration Goals
  > 1. Pages or Screens per Session

  1. Storing data and generating reports 5:44
  > There are 3 Scopes for dimensions and metrics
  >- hit-level
  >- session-level
  >- user-level

  1. Creating a measurement plan 3:00
  >- Macro conversions : Key actions that users take on websites that fulfill your business objectives like making a purchase


## Assessment 1
1. If default Google Analytics tracking code is installed on pages with different domains, Analytics will count these users and sessions separately.
  >- **True**
  >- False

2. What does Google Analytics call a URL that passes data parameters for reporting?
  >- A tag
  >- **A hit**
  >- A dimension
  >- A metric

3. When does the Google Analytics tracking code send a pageview hit to Analytics?
  >- Every time a user clicks a video
  >- Every time a user adds an item to a shopping cart
  >- Every time a user performs a search on a website
  >- **Every time a user loads a webpage**

4. When does the Google Analytics tracking code send an event hit to Analytics?
  >- Every time a user performs an action with pageview tracking
  >- Every time a user makes a reservation on a booking site
  >- Every time a user adds an event to their calendar
  >- **Every time a user performs an action with event tracking**

5. What does Google Analytics use to differentiate new and returning users?
(select all answers that apply)
  >- **A browser cookie**
  >- Artificial intelligence
  >- **A randomly-assigned unique identifier**
  >- A sequential unique identifier

6. What will happen if a user clears the Analytics cookie from their browser?
(select all answers that apply)
  >- Analytics will inform the user that they need to set a new Analytics cookie
  >- **Analytics will not be able to associate user behavior data with past data collected by the tracking code**
  >- **Analytics will set a new unique ID and browser cookie the next time a browser loads a tracked page**
  >- Analytics will automatically recognize returning users

7. By default, Google Analytics can recognize returning users over multiple sessions from different browsers and devices.
  >- True
  >- **False**
8. A session in Google Analytics times out after how many minutes by default?
  >- 5
  >- 15
  >- **30**
  >- 60

9. To send data to Google Analytics from a web-connected device like a point-of-sale system, what feature must be used?
  >- Data Import
  >- Browser cookies
  >- The Networking protocol
  >- **The Measurement Protocol**

10. For an event goal defined as playing a video, how many Goal conversions will Google Analytics record if that video is played three times in the same session?
  >- **1**
  >- 2
  >- 3
  >- 4

11. Which are Goal types in Google Analytics?
(select all answers that apply) (review Unit 1, Lesson 3)
  >- **Destination**
  >- Shopping Cart
  >- **Pages/Screens per session**
  >- **Duration**

12. If data is excluded from a view using a filter, it may be recovered within thirty days.
  >- True
  >- **False**

13. Which of these scopes could be used for dimensions and metrics?
(review Unit 1, Lesson 4)
  >- Event-level, session-level, or transaction-level scope
  >- Location-level, duration-level, or user-level scope
  >- **Hit-level, session-level, or user-level scope**
  >- Event-level, duration-level, or transaction-level scope

14. When defining a measurement plan, what is the order of steps?
  >- Business objectives > KPIs > key actions
  >- KPIs > key actions > business objectives
  >- Key actions > KPIs > business objectives
  >- **Business objectives > key actions > KPIs**

15. What are macro-conversions in a measurement plan?
  >- The metric data used to measure business success
  >- **The main website actions users take that accomplish stated business goals**
  >- The secondary website actions users take that lead to main actions
  >- A list of keyboard shortcuts for measurement tasks in Google Analytics

# 2. Setting Up Data Collection and Configuration
  1. Organize your Analytics account 5:26
    > Organization > Account > Property > view (Master, Test, Raw Data)
  1. Set up advanced filters on views 6:38
  1. Create your own Custom Dimensions 6:10
    > - Standard GA account can create up to 20 custom dimensions
    > - Google 360 account can crate 200 custom dimensions
  1. Create your own Custom Metrics 5:36
    >- There are only 2 scopes under custom metrics : Hit, Product
  1. Understand user behavior with Event Tracking 5:00
    >- Event tracking code will pass 4 parameters along with the event hit :
    >- Category
    >- Action
    >- Label
    >- Value

## Assessment 2
1. To collect data from two websites with different URLs using a single Google Analytics property, what feature must be set up?
>- Advanced filters
>- **Cross-domain tracking**
>- Event tracking
>- Custom Dimensions

2. Filters may be applied retroactively to any data that has already been processed.
>- True
>- **False**

3. To see data for users from the U.S. and Canada only in a view, which filter would be applied?
>- Filter 1: include U.S. > Filter 2: include Canada
>- Filter 1: include Canada > Filter 2: include U.S.
>- **Filter 1: include U.S. and Canada**
>- Filter 1: exclude Europe and Asia

4. To view data in reports by user categories such as Bronze, Gold, and Platinum status levels, what Google Analytics feature is needed to collect this data?
>- Event Tracking
>- Custom Metric
>- **Custom Dimension**
>- Custom Filter

5. To pair metrics with dimensions, what should they have in common?
>- Same creator
>- Same creation date
>- Same view
>- **Same scope**

6. To create a Custom Dimension for membership status (i.e., rewards level), what scope would be applied?
>- Hit
>- Product
>- Session
>- **User**

7. Custom Dimensions can be used in which reports? (select all answers that apply)
>- As primary dimensions in Standard reports
>- **As secondary dimensions in Standard reports**
>- **As primary dimensions in Custom Reports**
>- As custom metrics in Custom Reports

8. When a Custom Dimension is active, which data will it affect?
>- Data collected before the Custom Dimension was applied
>- **Data collected after the Custom Dimension was applied**
>- All of the data in the property
>- None of the data in the property

9. To collect the number of comments users posted to a website page, what feature would be used?
>- Custom Filter
>- Custom Dimension
>- **Custom Metric**
>- Custom Alert

10. Custom Metrics can have which scopes? (select all answers that apply)
>- **Hit**
>- **Product**
>- Session
>- User

11. What four parameters can be included with an event hit for reporting?
>- Category, Action, Label, Total Events
>- Category, Action, Label, Unique Events
>- **Category, Action, Label, Value**
>- Event, Category, Action, Label

12. If a user watches a video with event tracking three times in a single session, how many Unique Events will be counted?
>- 0
>- **1**
>- 2
>- 3

# 3. Advanced Analysis Tools and Techniques
  1. Segment data for insight 5:30
  1. Analyze data by channel 4:24


## Assessment 3

1. Segments applied to reports can analyze data for which of the following groups?
(select all answers that apply)

>- **Users 25 to 34 years of age who have their browser set to Spanish**
>- **Users who viewed a webpage, then watched a video**
>- **Users who engaged in social media or email campaigns**
>-  Users who have children under the age of 18

2. Custom segments may be created using which criteria?
(select all answers that apply)
 >- **Dimensions**
 >- **Metrics**
 >- **Session dates**
 >- **Sequences of user actions**

3. How many segments may be applied at once?
>-  1
>-  2
>-  3
>-  **4**

4. Because segments are applied before sampling, segmented data will not be sampled.
>-  True
>-  **False**

5. What report shows data segmented by channel?
>-  Segmentation
>-  Source/Medium
>-  **Channels**
>-  Attribution

6. Google Ads and Google Marketing Platform campaigns served on the Google Display Network are grouped into which channel?
>-  Paid Search
>-  Organic Search
>-  Direct
>-  **Display**

7. What report analyzes which webpages get the most traffic and highest engagement?
>-  Active Users report
>-  Engagement report
>-  **All Pages report**
>-  Frequency and Recency report

8. In a “last-click” attribution model, Google Analytics will attribute all of the conversion credit to which source(s)?
>-  First marketing activity
>-  **Last marketing activity**
>-  Single assisted conversion
>-  All assisted conversions

9. Multi-channel Funnel reports can credit conversions across which channels?
(select all answers that apply)
>-  **Website referrals**
>-  **Paid and organic search**
>-  **Custom campaigns**
>-  Television channels

10. How would Google Analytics credit a channel that contributed to a conversion prior to the final interaction?
>-  Primary conversion
>-  **Assisted conversion**
>-  Second-to-last-click attribution
>-  Last-click attribution

11. What report shows users who initiated sessions over 1-day, 7-day, 14-day, and 30-day periods?
>-  User Explorer report
>-  **Active Users report**
>-  Users Flow report
>-  Behavior Overview report

12. What report groups an audience based on acquisition date and compares behavior metrics over several weeks?
>-  Behavior Overview report
>-  Active Users report
>-  Users Flow report
>-  **Cohort Analysis report**

13. Custom Reports have which capabilities? (select all answers that apply)
>-  **Use multiple dimensions together in the same report**
>-  **Create a report with Custom Metrics**
>-  **Use a Custom Dimension as a primary dimension**
>-  Create a report with data-driven attribution

14. What type of Custom Report shows a static, sortable table with rows of data?
>-  Explorer
>-  **Flat Table**
>-  Map Overlay
>-  Pivot Table

15. Which would prevent data from appearing in a Custom Report? (select all answers that apply)
>-  **A filter that filters out all data**
>-  Not sharing the Custom report with users in the same view
>-  **Dimensions and metrics of different scopes**
>-  Too many dimensions applied to the Custom report



## Assessment 4

1. What is “remarketing” in Google Analytics?
>- When users visit a website for the first time and complete a conversion
>- **When users are shown targeted ads to bring them back to a website and encourage a conversion**
>- When Google Analytics can’t distinguish a new user because they have deleted their browser cookies
>- When a user buys an available product from a competitor

2. To enable remarketing in Google Analytics, what must first be enabled? (select all that apply)
  >- **Advertising Reporting Features**
  >- Demographics and Interests
  >- **Google Ads or Display & Video 360 account linking**
  >- Custom Dimension

3. Which remarketing audiences can be defined in Google Analytics? (select all that apply)
  >- **Users who visited a specific page on a website**
  >- **Users who played a video on a website**
  >- **Users who speak a particular language**
  >- Users who searched for a product on Google Search

4. Remarketing can show relevant ads on which Google properties? (select all that apply)
  >- **Google Display Network**
  >- Google Sites
  >- **Mobile apps**
  >- **Google Search**

5. What is the maximum duration a user can be included in a remarketing audience?
  >- 120 days
  >- 180 days
  >- 365 days
  >- **540 days**

6. What Google Analytics data can be used to define a remarketing audience? (select all that apply)
  >-  **Pre-defined Segment**
  >-  **Custom Segment**
  >-  Custom Dimension
  >-  Custom Metric

7. How many user cookies does an audience list require to be eligible for Google Ads Search Ad remarketing?
  >-  100
  >-  **1000**
  >-  2000
  >-  5000

8. Which users could be targeted with Dynamic Remarketing to bring them back to a website? (select all that apply)
  >- Users who posted a favorable product review
  >- **Users who viewed a website search result page**
  >- **Users who viewed product detail pages**
  >- **Users who abandoned their shopping carts**

9. To set up Dynamic Remarketing for a retail vertical, what must be linked to Google Ads?
>- The Google Search Center
>- The Google Analytics Center
>- **The Google Merchant Center**
>- The Google Help Center

10. To set up Dynamic Remarketing, what must first be created in Google Analytics?
>- Custom Segment
>- Custom Metric
>- **Custom Dimension**
>- Custom Report
