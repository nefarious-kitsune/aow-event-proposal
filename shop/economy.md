# Economy

[The AoW Ideas project](https://github.com/nefarious-kitsune/aow.ideas):
*Ideas from AoW players on changes & improvements to help make the game more interesting.*

# Problems

Purchase prices of various items are inconsistent and *off-balance*.


## Suggested Solution

* Create a table of *standard cost* of different item type for conversion.
* Derive all suggested prices from the same table.

## Standard Cost

| Item Type   | Base Value  |
| ----------  |     ------: |
| US$         | 1,000.00    |
| Gem         |    10.00    |
| Gold Coin   |     0.09    |
| [Silver Coins](silver-coin) |     5.00    |
| Medal       |    50.00    |

See [this spreadsheet](https://docs.google.com/spreadsheets/d/1H-fwDQQ0s69IslinISH4wpMzD3PCKLpDJ8i3VvjN1Gs/edit?usp=sharing) for the full list.

## Suggested Prices

Example calculations of *homogeneous* pack:

| Item                   |                  | Suggested Price | Listed Price | Bargain Value |
| ----------             | ---------------- |        ------: |      ------: | ----: |
| 800 Medal Daily Sale   | 800 × 50 ÷ 1000  |        $ 40.00 |       $ 9.99 |  200% |
| 5,000 Coins Sale       | 5000 × 0.09 ÷ 10 |         45 Gem |      100 Gem |   45% |

----

Example calculations of *heterogeneous* pack:

| Item                   |                     | Suggested Price | Listed Price | Bargain Value |
| ----------             | ----------------    |        ------: |      ------: | ----: |
| Legendary Hero         | 1 × 10000 ÷ 1000    |        $ 10.00 |              |       |
| 3× Super Card Vouchers | 3 × 2250  ÷ 1000    |         $ 6.75 |              |       |
| 50,000 Coins           | 50000 × 0.09 ÷ 1000 |         $ 4.50 |              |       |
| **Hero's Coronation**  |                     |    **$ 21.20** |   **$ 9.99** |  213% |

----

Example calculations of *randomized*, heterogeneous pack (80% mark-down):

| Item                   |                     | Suggested Price  | Listed Price | Bargain Value |
| ----------             | ----------------    |        ------:  |      ------: | ----: |
| 4-star Common Troops   | 1%  × 8,000 ÷ 0.09  |       889 Coin  |              |       |
| 4-star Rare Troops     | 93% × 12000 ÷ 0.09  |   124,000 Coin  |              |       |
| 4-star Epic Troops     | 6%  × 16000 ÷ 0.09  |    10,667 Coin  |              |       |
| *Sum*                  |                     | *135,556 Coin*  |              |       |
| **4-Star Troops Draw** | 80% × *135,556*     | **108,444 Coin** |   **120,000 Coin**  |  94% |
