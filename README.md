# Majsoul-to-NAGA
=Use Mahjong Soul Logs with NAGA AI analysis

== Summary
Capture Mahjong Soul logs from a replay using browser Greasemonkey script and
convert to format accepted by NAGA's custom game analysis

Copies NAGA-compatible output to clipboard when you press "s" while in a Mahjong Soul 4-player replay, which you can paste in https://naga.dmv.nico/naga_report/order_form/ for AI analysis of your game

== Instructions (Browser)
=== Install tempermonkey extenstion on your browser
https://www.tampermonkey.net/[Here]

=== Install `downloadlogsnaga` script
Add https://gist.githubusercontent.com/Equim-chan/875a232a2c1d31181df8b3a8704c3112/raw/a0533ae7a0ab0158ca9ad9771663e94b82b61572/downloadlogs.js[this script] to tempermonkey.

=== Download the log
Login to Mahjong Soul, open the log you want to review, then press kbd:[S] after the log is loaded.

=== Paste into NAGA custom analysis order form
Text is in the clipboard. Paste into https://naga.dmv.nico/naga_report/order_form/[Here]