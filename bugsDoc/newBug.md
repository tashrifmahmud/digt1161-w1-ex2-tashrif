# Bug Report: Cart Total Does Not Update After Quantity Change

> **Note:** This is a fictional bug report created for DIGT 1161 lab practice.

## Summary

The shopping cart total does not update immediately when the quantity of an item is changed.

## Environment

- Platform: Web
- Browser: Chrome
- Device: MacBook Air
- Connection: Wi-Fi

## Steps to Reproduce

1. Open the online store.
2. Add a product to the cart.
3. Open the cart page.
4. Change the item quantity from 1 to 2.
5. Observe the cart total.

## Expected Behaviour

The cart total should update immediately to reflect the new quantity.

## Actual Behaviour

The item quantity changes, but the cart total remains unchanged until the page is refreshed.

## Impact

This may confuse users because the quantity and total displayed on the page do not match.

## Notes

Refreshing the page updates the total correctly, so the issue appears to be related to the cart interface not refreshing automatically.

## Severity

**Medium** - the issue does not block checkout, but it may cause confusion because the displayed cart total becomes inconsistent with the selected quantity.

## Reproduction Frequency

Occurs consistently when the item quantity is changed without refreshing the page.