# polymer-outside-click
A polymer wrapper component for listening to outside click events

## How to use ```polymer-outside-click```?
Wrap your element using the ```polymer-outside-click``` and listen to the property passed into ```clicked```. ```polymer-outside-click``` will return ```true``` if you clicked outside of it or it will return ```false``` if you clicked inside.

```
<polymer-outside-click clicked={{clicked}}>
  <!-- Your element goes here -->
</polymer-outside-click>
```

## How to run the demo?
- Clone the repo
- Navigate to the repo using terminal
- Run ```bower install```
- Run ```polymer serve```
- Open your browser and go to ```your-polymer-development-url/demo```, (usually ```http://127.0.0.1:8081```)
