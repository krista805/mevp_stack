The V-ON directive is used to monitor events and bind that event to either an inline or Vue method. When the monitored event has been triggered, the bonded method will be triggered. 


- ex. click events
- <button v-on:click='methodName'></button>
OR
- <button @click='methodName'></button>