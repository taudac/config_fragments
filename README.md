DYNAMIC DEBUG
=============

Enabling using kernel command line parameters
---------------------------------------------

Example for loadable (not builtin modules), add the following to
`/boot/cmdline.txt` (without newlines):	

	dynamic_debug.verbose=1
	clk_si5351.dyndbg=+p
	snd_soc_wm8741.dyndbg=+p
	snd_soc_bcm2708_i2s.dyndbg=+p
	snd_soc_tau_dac.dyndbg=+p

