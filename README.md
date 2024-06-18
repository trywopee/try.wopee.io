<!-- # Try Wopee.io -->

## 0. Demo app

For a quick demo, you can use the following form to get a deployment of demo app for you. You will get a unique URL to access your app.

1. ⚙️ Deploy `demo-app-v1`:
   <iframe src="https://hub.wopee.io/form/get-demo-app" width="500px" height="410px"></iframe>
2. ☕️ Wait up to 1 mintue for the deployment to finish
3. 🚀 Check your app using the provided URL

## 1. Analysis

1. 👉 **Sign up** to [cmd.Wopee.io](https://cmd.wopee.io)
2. 👉 Create a `NEW PROJECT` inserting a **URL of your demo app** deployment
3. 🍿 Watch introduction video
4. 👀 Explore generated **test scenarios** with the test step details and auto-approved baselines.

Your project is: ready for the *first testing*.

## 2. Stability test

1. 👉 `START TESTING` your project at [cmd.Wopee.io](https://cmd.wopee.io)
2. 📊 Check the results
   - Everything should `PASS` this time - no differences found

Your project is: ready for the *regular checks* of the app stability. You can verify by `START TESTING`.

## 3. Regression test

1. ⚙️ Deploy `demo-app-v2` using [form above](https://try.wopee.io)
2. 👉 `START TESTING`
   - In the meantime: Check how Demo App v2 looks like and try to spot difference by your own
3. 📊 Check the results
   - Focus on tests with status `Unresolved` - found differences
4. ✅ Calibrate the baselines
   - 👍 `APPROVE` screenshots with **correct** new look of Demo App v2 (setup new baseline)
   - 👎 `REJECT` screenshots with visually detected **defects** (keep original baseline)

Your project is: *adjusted* with the current app version (demo-app-v2). You can verify by `START TESTING`.

## 4. Fine tuning

1. ⚙️ Deploy `demo-app-v3` using [form above](https://try.wopee.io)
2. 👉 `START TESTING`
3. 📊 Check the results
4. ➕ Set ingore areas on screenshots with dynamic content.
   - Check if those screenshots are having `OK` status now.

Your project is: *stabilised* with the dynamic parts of the current app version (demo-app-v3). You can verify by `START TESTING`.
