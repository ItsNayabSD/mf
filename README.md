# Mutual Funds

* <a href="#depend">Install dependencies</a>
* <a href="#run">Run the program</a>
* <a href="#xirrp">Example given in the xirr.js file</a>

<h2 id="depend">Install dependencies</h2>

To run with `node`, install `moment.js`.

```
npm install moment
```

<h2 id="run">Run the program</h2>

```
npm xirr.js
```
<h2 id="xirrp">Example given in the xirr.js file</h2>

| Amount | Dates |
|--------|-------|
|-10000|2019-06-14|
|-10000|2019-06-17|
|-2500|2019-09-05|
|22726|2019-09-21|

After running the program the result is:

```
4.2089862515264205
```
This is the same result when we execute `xirr` function in Google sheets or Microsoft Excel.
