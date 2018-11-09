segger_rtt_srcs = files([
  'RTT/SEGGER_RTT.c',
  'RTT/SEGGER_RTT_printf.c',
  'Syscalls/SEGGER_RTT_Syscalls_GCC.c',
])

segger_rtt_incdirs = include_directories([
  'RTT',
])

segger_rtt_lib = static_library(
  'segger_rtt',
  [segger_rtt_srcs] ,
  c_args              : [c_args],
  include_directories : [config_incdirs, segger_rtt_incdirs]
)
