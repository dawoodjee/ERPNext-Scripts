# ERPNext-Scripts
Various unrelated ERPNext Scripts.

## 1. Weighted Barcode
The Weighted Barcode Script allows scanning of scale printed weight barcode into the POS. Replace your pos.js file and customise it according [these instructions](https://discuss.erpnext.com/t/how-can-mange-barcode-for-weighted-items-in-pos/20066/) to suit your barcode format.

1. Get this [pos.js file](https://github.com/dawoodjee/ERPNext-Scripts/blob/master/pos.js)

2. Then replace `pos.js` located at `~/frappe-bench/apps/erpnext/erpnext/accounts/page/pos/pos.js`

OR just copy and paste everything to your `pos.js`.

3. cd ~/frappe-bench

4. bench build


### Compatibility
* Tested with ERPNext v7.x to v10.x.
* Works best with Firefox browser. There is an issue with Google Chrome.


---


## Issues
Please report any issues to [this discussion thread](https://discuss.erpnext.com/t/how-can-mange-barcode-for-weighted-items-in-pos/20066/). Push requests (your edits) are welcome!




