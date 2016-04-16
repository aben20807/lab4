question A:<br>
nm ./questionA<br>
output:<br>
0000000000600e50 d _DYNAMIC<br>
0000000000600fe8 d _GLOBAL_OFFSET_TABLE_<br>
0000000000400608 R _IO_stdin_used<br>
w _Jv_RegisterClasses<br>
00000000004004b4 T _Z7averagePdRd<br>
00000000004004e2 T _Z7averageif<br>
0000000000600e30 d __CTOR_END__<br>
0000000000600e28 d __CTOR_LIST__<br>
0000000000600e40 D __DTOR_END__<br>
0000000000600e38 d __DTOR_LIST__<br>
0000000000400738 r __FRAME_END__<br>
0000000000600e48 d __JCR_END__<br>
0000000000600e48 d __JCR_LIST__<br>
0000000000601018 A __bss_start<br>
0000000000601008 D __data_start<br>
00000000004005c0 t __do_global_ctors_aux<br>
0000000000400420 t __do_global_dtors_aux<br>
0000000000601010 D __dso_handle<br>
w __gmon_start__<br>
0000000000600e24 d __init_array_end<br>
0000000000600e24 d __init_array_start<br>
00000000004005b0 T __libc_csu_fini<br>
0000000000400520 T __libc_csu_init<br>
U __libc_start_main@@GLIBC_2.2.5<br>
0000000000601018 A _edata<br>
0000000000601028 A _end<br>
00000000004005f8 T _fini<br>
0000000000400390 T _init<br>
00000000004003d0 T _start<br>
00000000004003fc t call_gmon_start<br>
0000000000601018 b completed.6531<br>
0000000000601008 W data_start<br>
0000000000601020 b dtor_idx.6533<br>
0000000000400490 t frame_dummy<br>
000000000040050a T main<br>
<br>
Among them<br>
00000000004004b4 T _Z7averagePdRd<br>
00000000004004e2 T _Z7averageif<br>
are the encoded identifiers being used for the functions.<br>
_<br>
question B:
./questionB
output:<br>
1 8<br>
4 8<br>
4 8<br>
8 8<br>
<br>
The former numbers of each lines represent the size of each type.<br>
For example: <br>
The size of a variable which type is char is one byte.<br>
The size of a variable which type is int is four bytes.<br>
The size of a variable which type is float is four bytes.<br>
The size of a variable which type is double is eight bytes.<br>
<br>
The latter numbers of each lines represent the size of address which point to each type.<br>
Conseqently, the each size numbers are eight bytes.<br>
