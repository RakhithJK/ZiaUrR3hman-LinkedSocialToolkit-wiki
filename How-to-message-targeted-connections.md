LinkedIn’s messaging platform has taken the business world by storm in recent years. It’s a proven site for lead generation and almost all of the sales teams of B2B companies rely on messaging to generate leads. It’s the perfect platform for sharing content, creating connections, and closing business deals. So let’s get started on how you can start messaging others using **Linked Social Toolkit**.

There are two ways to send a mass messages to all your connections
1. [Message all connections](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/wiki/How-to-mass-message-all-your-connections)
2. Message targeted connections

## Message targeted connections
You can message your targeted connections using search and other filters. Click on “**Message targeted users**” button from  **Linked Social Toolkit** left menu then you will see dialog as below

![How to mass message targeted user on LinkedIn](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/How-to-message-targeted-connections.png)

Follow these steps for sending customized message to your contacts
1. Create or select a campaign
2. Write your message
2. Find your targeted audience using search filters
3. Click on "**Send**" button

## Feature explanation
### Create a campaign
First, you need to create a campaign for sending messages. Click on plus icon to create a new campaign or select old campaign from drop down.

![create a Campaign for sending messages](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/create-a-campaign.png)

### Manage campaign
Click on **Manage campaign** option to **edit** or **delete** campaigns.

![Manage campaign](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/manage-campaign.png)

### Adding already contacted user to some campaign
If you have sent any messages to your connections using any other tool or script or extension etc. or even manually and you don’t want to send message again to your connection, then this feature is used.

Another use-case for using this feature is, if you have removed Tampermonkey extension or uninstalled your browser or installed new Operation System (Windows, Mac or Linux), then Script database also gets removed.  When you re-install the script and start sending messages to your connections, then script would send duplicate messages because Script doesn’t have data about old campaigns. So, use feature to avoid sending duplicate messages to your connections. You need to use the feature before sending messages.
Click ![addCUC](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/addCUC.png) icon then confirm the dialog and wait until script finishes the process.

![Adding already contacted user to some campaign](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Adding-already-contacted-user-to-some-campaign.png)

### Message
Enter your message in message text box. You can use **@name** for full name, **@firstName** for first name and **@lastName** for last name of user. All these short-codes are case-sensitive.

![Message](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Message.png)

### Exclude message to 
If you want to avoid or exclude or stop your specific connections from sending message, then type connection name in input field then press **Enter key** or click search button. Connections list matching your criteria will be shown, just select the right connection. **Tab key** could also be used to navigate through search results. Use Enter key or left click for selecting your connection.
 
![Exclude-message-to](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Exclude-message-to.png)

### Exclude connections from campaign
If you don’t want to send message to your connections whom you have already sent messages using another campaign, then check that campaign name to avoid or exclude or stop connections from sending message.

![Exclude-connections-from-campaign](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Exclude-connections-from-campaign.png)

### Search
![Search](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Search.png)

This search field is equivalent to LinkedIn default search bar. You can use the **Search** to look for people with similar interests, role models, and Influencers to broaden your professional network and expertise.
To search for a specific person, enter your keyword into the Search field.

**Notes**
* You can search using keywords such as company or job title. For example, you can search for “**Richard Branson Founder**".
* If you don’t know the full name of the person you’re searching for, enter other information that you know about them. For example, you can search for “**Editor The Kansas City Star**”.
* You can also search for multiple people by typing your search criteria into the search bar.
Keep search field blank, if you don’t want to search by keyword or search term.

### Using Boolean search
You can run a Boolean search on by combining keywords with operators like AND, NOT, and OR during your search.
Here are some ways to use Boolean logic and construct your searches:
* **Quoted searches**: For an exact phrase, enclose the phrase in quotation marks. For example, type "product manager". You can also use quotation marks if you want to find someone with a multi-word title.
	* Search only supports standard, straight quotation marks ("). Other software or websites may use special symbols that our system does not recognize. Curly quotation marks (“), also known as smart quotes or typographer's quotes, aren't supported.
	* In order to optimize overall site performance, stop words such as "by", "in", "with", etc. aren't used.

* **NOT searches**: Type the word NOT (capital letters) immediately before a search term to exclude it from your search results. This typically limits your search results. For example, "programmer NOT manager".

* **OR searches**: Type the word OR (capital letters) to see results that include one or more items in a list. This typically broadens your search results. For example, "sales OR marketing OR advertising”.

* **AND searches**: Type the word AND (capital letters) to see results that include all items in a list. This typically limits your search results. For example, "accountant AND finance AND CPA".

* **Parenthetical searches**: To do a complex search, you can combine terms using parentheses. For example, to find people who have "VP" in their profiles, but exclude "assistant to VP" or SVPs, type **VP NOT (assistant OR SVP)** in search field.

![Boolean Search](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Boolean-Search.png)

When handling searches, the overall order to precedence is:
1. Quotes [""]
2. Parentheses [()]
3. NOT
4. AND
5. OR

**Important**
* The + and - operators are not officially supported. Using AND in place of + and NOT in place of - makes a query much easier to read and guarantees that we'll handle the search correctly.
* When using NOT, AND, or OR operators, you must type them in uppercase letters.

### Using Search Operators
You can use search operators directly in search bar to narrow your results. Search operators complement the filters found on the right rail of the results page, as well as the Boolean operators AND, OR, and NOT.
There are five search operators currently supported:
* **firstname**- Finds members based on first name
* **lastname**- Finds members based on last name
* **title**- Finds members based on their current job title
* **company**- Finds members based on their current company (keyword search)
* **school**- Finds members based on schools attended (keyword search)
For example, to search for current software engineers not named Doe, who have attended either Harvard University or Stanford University, use following query in search field:

**title:"software engineer" NOT lastname:doe School(harvard OR stanford)**

![Using Search Operators](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Using-Search-Operators.png)

### Tips for Using Search Operators
* Use quotes for multi-word search terms.
* Use parentheses for AND, OR and NOT phrases.
* Commas should not be included in between multiple search operators.
* Spaces should not be included in between the search operator and the search term, such as **lastname:doe**.
* Wildcard "*" searches not supported. 

### Keywords search filter
You can filter search using advance keywords filter for first name, last name, title, company name and school name. keep these blank if you don’t want to use.

![Keywords search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Keywords-search-filter.png)

### Connection of search filter
This search filter is used to search for common or mutual connections. Click on “**Connections of**” tab. Type your connection name, press enter button or click search icon. From search results select your connection.

![Connection of search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Connection-of-search-filter.png)

### Location search filter
When searching for people or jobs, you can limit your search to single or multiple locations.
#### Entering locations in your search filed
Enter your search term in the Search field at the top of script interface.
For example: product manager California

![Entering locations in your search filed](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Search.png)

#### Filtering searches using the Locations filter
You can limit your search to single or multiple locations by using the Locations. To filter your search using the Locations filter click on “**Locations**” tab, enter the location name in the location search field, press enter button or click search icon. From search results select location.  You can add multiple locations in the same search.

![Filtering searches using the Locations filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Filtering-searches-using-the-Locations-filter.png)

### Current and past companies search filter
Used to filter connections by their current companies or past companies. Click on “**Current companies**” tab, enter the company name in the company search field, press enter key or click search icon. From search results select company. You can add multiple companies in the same search.

![Current companies search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Current-companies-search-filter.png)
![Past companies search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Past-companies-search-filter.png)

### Industries search filter
Used to filter connections by Industries. Click on “**Industries**” tab, enter the industry name in the industry search field, press enter key or click search icon. From search results select industry. You can add multiple industries in the same search.

![Industries search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Industries-search-filter.png)

### School search filter
Used to filter connections by their school, university or college name. Click on “**School**” tab, enter the school name in the school search field, press enter key or click search icon. From search results select school. You can add multiple schools in the same search.

![School search filter](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/School-search-filter.png)


### Total message
This is the total number connections you want to send messages.
### Delay
This is the delay between each message in seconds. 
### Start position
Start position 0 would be the first record in your [search result](https://www.linkedin.com/search/results/people/?facetNetwork=%5B%22F%22%5D&origin=FACETED_SEARCH).

![Start position](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/Start-position-Search.png)

### Attachments
You can send images and files as attachments with your message. Click on “**Attach an image**” or “**Attach a file**”, then select your attachment. You can also add multiple attachments with single message script will save your attachment.

![send-images-and-files-as-attachments-with-your-message](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/send-images-and-files-as-attachments-with-your-message.png)

### Profile views
To send profile view notification to connection whom you are sending message just check the “**Send profile view notification**” checkbox.

![Send profile view notification to connection whom you are sending message](https://github.com/ZiaUrR3hman/LinkedSocialToolkit/raw/master/images/send-profile-view.png)

Click on “**Stop script execution**” button from **Linked Social Toolkit** left menu to stop script from sending messages.
