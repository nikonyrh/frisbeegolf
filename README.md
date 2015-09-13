FrisbeeGolf score tracker
=========================

A fairly trivial HTML+JS page to keep track of frisbee golf results, currently only has map info
on Tali (Espoo Finland, see https://www.youtube.com/watch?v=vRG_w_gcgyc for an introduction).

Current minimal proto supports only score calculation but has no peristence or any server-sided code,
there are quite many features to be implemented.

All interactions occur via four buttons with following actions (also bound to PC keyboard keys for easier testing):
- Left: go to previous player
- Right: go to next player
- Up: Increase the score by one
- Down: Decrease the score by one

TODO
--------
- Nicer UI, better auto-scaling for mobile
- User-defined list of player names
- Persistence on localStorage, checking of results on earlier games
- Optional synchronization to "cloud", possibly written in PHP
- Account and group creation
- More map information available, stored server-side

Pull requests are welcome :)
