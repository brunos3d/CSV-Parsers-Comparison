# CSV-Readers-Comparison

🔥 NODE.JS - Comparative analysis of csv file readers and converters.

| module         | execution time |
| -------------- | -------------- |
| csvtojsonV1.js | 8.319901 ms    |
| csvtojsonV2.js | 13.875601 ms   |

## Modules

The comparator consists of modules.
The modules are called by the [index.js](./index.js) file that calls the `execute` function passing the csv `data`,
they are in the [readers](./readers/) folder and maintain the following structure:

```js
module.exports = {
    execute(data, stopCallback) {
        // Your code here
        stopCallback();
    }
};
```

## Test Data

The tests were based on the [sample-data.csv](./sample-data.csv) file which maintains the following structure:

| \_id                     | age | name              | gender | email                      | phone              |
| ------------------------ | --- | ----------------- | ------ | -------------------------- | ------------------ |
| 5e327d46d2bced0625350c64 | 20  | Kimberley Kinney  | female | kimberleykinney@quarx.com  | +55 (923) 451-3229 |
| 5e327d4652112a31ca1cb009 | 25  | Frieda Roth       | female | friedaroth@quarx.com       | +55 (928) 580-3096 |
| 5e327d4611b7676779e8706f | 31  | Bean Pope         | male   | beanpope@quarx.com         | +55 (839) 449-2320 |
| 5e327d46abc4381ea5704c24 | 34  | Rosetta Burks     | female | rosettaburks@quarx.com     | +55 (867) 587-3346 |
| 5e327d461fe8198e46fbe6df | 36  | Finley Johns      | male   | finleyjohns@quarx.com      | +55 (911) 578-3351 |
| 5e327d46321cf15d280f2c9d | 38  | Nielsen Rutledge  | male   | nielsenrutledge@quarx.com  | +55 (948) 406-3975 |
| 5e327d4630b2bcfe8e500c34 | 23  | Herman Colon      | male   | hermancolon@quarx.com      | +55 (861) 532-2341 |
| 5e327d46211ace1737eef2ca | 40  | Lucinda Reilly    | female | lucindareilly@quarx.com    | +55 (984) 563-3741 |
| 5e327d46931914f68245cbd1 | 20  | Swanson Lopez     | male   | swansonlopez@quarx.com     | +55 (977) 557-2674 |
| 5e327d46c18553d99a42bfea | 25  | Christian Shaffer | female | christianshaffer@quarx.com | +55 (836) 589-3118 |
|                          |
