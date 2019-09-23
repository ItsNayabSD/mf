# Mutual Funds

JS function to calculate XIRR for mutual funds.

* <a href="#depend">Install dependencies</a>
* <a href="#run">Run the program</a>
* <a href="#xirrp">Example given in the xirr.js file</a>
* <a href="#waar">Weighted average annualized return</a>

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

* <h2 id="waar">Weighted average annualized return</h2>

Weighted average annualized return = ((MF1 Invested amount * MF1 XIRR) + (MF2 Invested amount * MF2 XIRR) + ....) / (MF1 Invested amount + MF2 Invested amount + ....)
