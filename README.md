# calendar-picker

This calendar picker has logic to handle choosing a start and end time. It was styled with [styled-components](https://styled-components.com/).

![Alt Text](https://github.com/venky4c/calendar-picker/blob/master/dist/src/CalendarPicker.gif)

### React skills used in this app

- CSS-in-JS: [styled-components](https://github.com/venky4c/calendar-picker/blob/master/dist/src/App.js) were used to conditionally bring effects to the start and end dates when chosen
```javasript
${(props) => {
    return (
      props.isInBetween &&
      css`
        background: #253847 !important;
        color: #eee;
      `
    );
  }}
```
- *A very simple app shows how we can build a nice calendar with just use of React useState() hooks, Component communication & styled components.* 
