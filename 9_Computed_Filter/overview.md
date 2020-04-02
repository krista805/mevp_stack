Computed and Filter

- Filter: Only use for simple text formatting
- Computed: All complicated and calculation handlings should be done with computed


- Filter:
ex. you want to capitalize the message, you would add in a filter. Name the filter 'capitalize' and place inside 2 places in HTML: 1. Inside double nested curly braces and 2. in v-bind directive. Sample of adding the capitalize filter - {{ message | capitalize}}. You would need to add a new property (filters:{})behind the data property.


- Computed. There are 3 things to remember...
1. Both data and computer can serve as a data source
    - ex. the <p> tag can get it's value from data as well as computed
2. Data and computed could NEVER share the property name (eg. 'message:')
3. Value in computed must be an anonymous function


COMPUTED can retireve value from data as well as change value from data