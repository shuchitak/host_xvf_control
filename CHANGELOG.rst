Host XVF Control change log
===========================

2.0.1
-----

  * ADDED: ``--band`` option for the NL Model band index
  * CHANGED: Added compiler option to treat all warnings as errors

2.0.0
-----

  * ADDED: Intertransaction delay configuration for SPI via command map shared library
  * ADDED: Support for the USB communication with the device

1.0.0
-----

  * ADDED: ``--version`` option
  * ADDED: ``--bypass-range-check`` and ``command-map-path`` options
  * ADDED: Autogenerated ``control_ret_t`` enum value to string map file
  * ADDED: calls to the ``get_cmd_*`` functions from the ``comamnd_map`` dynamic library
  * ADDED: call to the ``range_check`` function from the ``command_map`` dynamic library
  * CHANGED: Error messages for the hanging resource
  * CHANGED: Device no longer fetches the information to initialize itself from the ``command_map``
  * CHANGED: Moved ``print_arg`` into the ``command_map`` dynamic library
  * CHANGED: All internal host application errors are now ``255``
  * FIXED: UINT8 value overwrite in ``cmd_arg_srt_to_val`` function

0.2.0
-----

  * FIXED: ``--execute-command-list`` option
  * ADDED: ``hidden_cmd`` flag in ``cmd_t`` structure
  * ADDED: Builds for x86 Mac and Windows
  * CHANGED: UI for ``--help`` and ``--list-commands`` options
  * ADDED: ``--test-bytestream`` option for internal testing

0.1.0
-----

  * ADDED: Initial host app: it supports control over I2C and SPI on a Raspberry Pi
