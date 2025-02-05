# FAQ

Q: How do I get latest hellen-one?

A: ``.github/workflows/update-hellen-one-reference.yaml`` is set to pull latest hellen daily!

Q: I get error 'Cannot stat xx-yy__zz.kicad_pcb: No such file' but files are right there?

A: please do not use dashes and underscore symbols in file names.

Q: Automation says that aux_axis_origin is missing?

A: aux_axis_origin is required, please place it in the appropriate corner.

Q: I get "Cannot parse position" with negative value?

A: Please move origin point into left-bottom corner of the board since we cannot parse negative coordinates at the moment. See https://github.com/andreika-git/hellen-one/issues/349

Q: I am placing an order with JLCPCB and component orientation all looks wrong?!

A: See https://github.com/rusefi/uaefi/?tab=readme-ov-file#q-ive-place-an-order-with-jlcpcb-and-i-see-scary-looking-wrong-orientation

Q: What about firmware?

A: See https://github.com/rusefi/fw-custom-hellen144-f4 and https://github.com/rusefi/rusefi/wiki/Custom-Firmware

Q: Automation seems to work but files are not updated?

A: automation requires that you use default branch 'main'

