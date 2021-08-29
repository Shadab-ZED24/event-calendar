## Spring Calendar
 It's a React based component which provides the functionality of a full-calendar that 
 shows daily events. 

## Installation


 `npm install event-calendar`

```js 
import React from 'react';
import SpringCalendar from 'spring-calendar';

Set Some default Events.

let events=[
    {
        title:'Event 1',
        startDate:'2021-08-15 08:00',
        endDate:'2021-08-15 10:00',
    },
    {
        title:'Event 3',
        startDate:'2021-08-15 09:00',
        endDate:'2021-08-15 12:00',
    }
   
]
const App =()=> <SpringCalendar locale="en" events={events} color="#002651" defaultType="year"/>;
export default App
```