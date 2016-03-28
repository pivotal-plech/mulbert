# Mulpert
## Pivotal UI CSS All

I've had a lot of people asking for a simple static site generator with Pivotal UI and the latest styles.

I'm still using `dr-frankenstyle`. I'm building PUI by:

1. `npm i -g dr-frankenstyle`
1. `npm install --save pui-css-all`
1. `npm install --save-dev jquery`
1. `npm install --save-dev bootstrap`
1. `dr-frankenstyle ./source/styesheets/pui/`

Run Middleman
1. `middleman server`

**Note:** I'm still not including jquery or bootstrap in the layout.
