UI Mapping Change:

keyboard-layout-editor.com
import json from this directory and change mapping

QMK changes:

make changes in custom_config.h then compile with

`qmk flash -c -kb beekeeb/piantor -km manna-harbour_miryoku -e MIRYOKU_CLIPBOARD=MAC -e MIRYOKU_LAYERS=FLIP -e MIRYOKU_NAV=INVERTEDT`

tutorial:
https://github.com/manna-harbour/miryoku/discussions/85
