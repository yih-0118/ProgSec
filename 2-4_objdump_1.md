```c
PLAYGROUND:     file format elf64-littleaarch64


Disassembly of section .interp:

0000000000000238 <.interp>:
 238:	objdump: unrecognised disassembler option: intel
62696c2f 	.inst	0x62696c2f ; undefined
 23c:	2d646c2f 	ldp	s15, s27, [x1, #-224]
 240:	756e696c 	.inst	0x756e696c ; undefined
 244:	61612d78 	.inst	0x61612d78 ; undefined
 248:	36686372 	tbz	w18, #13, eb4 <__FRAME_END__+0x5bc>
 24c:	6f732e34 	.inst	0x6f732e34 ; undefined
 250:	Address 0x0000000000000250 is out of bounds.


Disassembly of section .note.gnu.build-id:

0000000000000254 <.note.gnu.build-id>:
 254:	00000004 	udf	#4
 258:	00000014 	udf	#20
 25c:	00000003 	udf	#3
 260:	00554e47 	.inst	0x00554e47 ; undefined
 264:	bcf4ed2f 	.inst	0xbcf4ed2f ; undefined
 268:	87a7d1be 	.inst	0x87a7d1be ; undefined
 26c:	f2688523 	ands	x3, x9, #0x3ffffffff000000
 270:	c957ba2d 	.inst	0xc957ba2d ; undefined
 274:	4a587f4b 	eor	w11, w26, w24, lsr #31

Disassembly of section .note.ABI-tag:

0000000000000278 <__abi_tag>:
 278:	00000004 	udf	#4
 27c:	00000010 	udf	#16
 280:	00000001 	udf	#1
 284:	00554e47 	.inst	0x00554e47 ; undefined
 288:	00000000 	udf	#0
 28c:	00000003 	udf	#3
 290:	00000007 	udf	#7
 294:	00000000 	udf	#0

Disassembly of section .gnu.hash:

0000000000000298 <.gnu.hash>:
 298:	00000001 	udf	#1
 29c:	00000001 	udf	#1
 2a0:	00000001 	udf	#1
	...

Disassembly of section .dynsym:

00000000000002b8 <.dynsym>:
	...
 2d4:	000b0003 	.inst	0x000b0003 ; undefined
 2d8:	000005b8 	udf	#1464
	...
 2ec:	00160003 	.inst	0x00160003 ; undefined
 2f0:	00011000 	.inst	0x00011000 ; undefined
	...
 300:	00000010 	udf	#16
 304:	00000012 	udf	#18
	...
 318:	0000004f 	udf	#79
 31c:	00000020 	udf	#32
	...
 330:	00000001 	udf	#1
 334:	00000022 	udf	#34
	...
 348:	0000006b 	udf	#107
 34c:	00000020 	udf	#32
	...
 360:	00000022 	udf	#34
 364:	00000012 	udf	#18
	...
 378:	0000007a 	udf	#122
 37c:	00000020 	udf	#32
	...
 390:	00000028 	udf	#40
 394:	00000012 	udf	#18
	...

Disassembly of section .dynstr:

00000000000003a8 <.dynstr>:
 3a8:	635f5f00 	.inst	0x635f5f00 ; undefined
 3ac:	665f6178 	.inst	0x665f6178 ; undefined
 3b0:	6c616e69 	ldnp	d9, d27, [x19, #-496]
 3b4:	00657a69 	.inst	0x00657a69 ; undefined
 3b8:	696c5f5f 	ldpsw	xzr, x23, [x26, #-160]
 3bc:	735f6362 	.inst	0x735f6362 ; undefined
 3c0:	74726174 	.inst	0x74726174 ; undefined
 3c4:	69616d5f 	ldpsw	xzr, x27, [x10, #-248]
 3c8:	6261006e 	.inst	0x6261006e ; undefined
 3cc:	0074726f 	.inst	0x0074726f ; undefined
 3d0:	6e697270 	uabdl2	v16.4s, v19.8h, v9.8h
 3d4:	6c006674 	stnp	d20, d25, [x19]
 3d8:	2e636269 	rsubhn	v9.4h, v19.4s, v3.4s
 3dc:	362e6f73 	tbz	w19, #5, ffffffffffffd1c8 <__bss_end__+0xfffffffffffec1b0>
 3e0:	494c4700 	.inst	0x494c4700 ; undefined
 3e4:	325f4342 	.inst	0x325f4342 ; undefined
 3e8:	0037312e 	.inst	0x0037312e ; NYI
 3ec:	42494c47 	.inst	0x42494c47 ; undefined
 3f0:	2e325f43 	uqrshl	v3.8b, v26.8b, v18.8b
 3f4:	5f003433 	.inst	0x5f003433 ; undefined
 3f8:	5f4d5449 	shl	d9, d2, #13
 3fc:	65726564 	fnmls	z4.h, p1/m, z11.h, z18.h
 400:	74736967 	.inst	0x74736967 ; undefined
 404:	4d547265 	.inst	0x4d547265 ; undefined
 408:	6e6f6c43 	umin	v3.8h, v2.8h, v15.8h
 40c:	62615465 	.inst	0x62615465 ; undefined
 410:	5f00656c 	.inst	0x5f00656c ; undefined
 414:	6f6d675f 	sqshlu	v31.2d, v26.2d, #45
 418:	74735f6e 	.inst	0x74735f6e ; undefined
 41c:	5f747261 	sqdmlsl	s1, h19, v4.h[3]
 420:	495f005f 	.inst	0x495f005f ; undefined
 424:	725f4d54 	.inst	0x725f4d54 ; undefined
 428:	73696765 	.inst	0x73696765 ; undefined
 42c:	54726574 	bc.mi	e50d8 <__bss_end__+0xd40c0>  // bc.first
 430:	6f6c434d 	mls	v13.8h, v26.8h, v12.h[2]
 434:	6154656e 	.inst	0x6154656e ; undefined
 438:	00656c62 	.inst	0x00656c62 ; undefined

Disassembly of section .gnu.version:

000000000000043c <.gnu.version>:
 43c:	00000000 	udf	#0
 440:	00020000 	.inst	0x00020000 ; undefined
 444:	00030001 	.inst	0x00030001 ; undefined
 448:	00030001 	.inst	0x00030001 ; undefined
 44c:	00030001 	.inst	0x00030001 ; undefined

Disassembly of section .gnu.version_r:

0000000000000450 <.gnu.version_r>:
 450:	00020001 	.inst	0x00020001 ; undefined
 454:	0000002f 	udf	#47
 458:	00000010 	udf	#16
 45c:	00000000 	udf	#0
 460:	06969197 	.inst	0x06969197 ; undefined
 464:	00030000 	.inst	0x00030000 ; undefined
 468:	00000039 	udf	#57
 46c:	00000010 	udf	#16
 470:	069691b4 	.inst	0x069691b4 ; undefined
 474:	00020000 	.inst	0x00020000 ; undefined
 478:	00000044 	udf	#68
 47c:	00000000 	udf	#0

Disassembly of section .rela.dyn:

0000000000000480 <.rela.dyn>:
 480:	00010d90 	.inst	0x00010d90 ; undefined
 484:	00000000 	udf	#0
 488:	00000403 	udf	#1027
 48c:	00000000 	udf	#0
 490:	00000750 	udf	#1872
 494:	00000000 	udf	#0
 498:	00010d98 	.inst	0x00010d98 ; undefined
 49c:	00000000 	udf	#0
 4a0:	00000403 	udf	#1027
 4a4:	00000000 	udf	#0
 4a8:	00000700 	udf	#1792
 4ac:	00000000 	udf	#0
 4b0:	00010ff0 	.inst	0x00010ff0 ; undefined
 4b4:	00000000 	udf	#0
 4b8:	00000403 	udf	#1027
 4bc:	00000000 	udf	#0
 4c0:	00000790 	udf	#1936
 4c4:	00000000 	udf	#0
 4c8:	00011008 	.inst	0x00011008 ; undefined
 4cc:	00000000 	udf	#0
 4d0:	00000403 	udf	#1027
 4d4:	00000000 	udf	#0
 4d8:	00011008 	.inst	0x00011008 ; undefined
 4dc:	00000000 	udf	#0
 4e0:	00010fd8 	.inst	0x00010fd8 ; undefined
 4e4:	00000000 	udf	#0
 4e8:	00000401 	udf	#1025
 4ec:	00000004 	udf	#4
	...
 4f8:	00010fe0 	.inst	0x00010fe0 ; undefined
 4fc:	00000000 	udf	#0
 500:	00000401 	udf	#1025
 504:	00000005 	udf	#5
	...
 510:	00010fe8 	.inst	0x00010fe8 ; undefined
 514:	00000000 	udf	#0
 518:	00000401 	udf	#1025
 51c:	00000006 	udf	#6
	...
 528:	00010ff8 	.inst	0x00010ff8 ; undefined
 52c:	00000000 	udf	#0
 530:	00000401 	udf	#1025
 534:	00000008 	udf	#8
	...

Disassembly of section .rela.plt:

0000000000000540 <.rela.plt>:
 540:	00010fa8 	.inst	0x00010fa8 ; undefined
 544:	00000000 	udf	#0
 548:	00000402 	udf	#1026
 54c:	00000003 	udf	#3
	...
 558:	00010fb0 	.inst	0x00010fb0 ; undefined
 55c:	00000000 	udf	#0
 560:	00000402 	udf	#1026
 564:	00000005 	udf	#5
	...
 570:	00010fb8 	.inst	0x00010fb8 ; undefined
 574:	00000000 	udf	#0
 578:	00000402 	udf	#1026
 57c:	00000006 	udf	#6
	...
 588:	00010fc0 	.inst	0x00010fc0 ; undefined
 58c:	00000000 	udf	#0
 590:	00000402 	udf	#1026
 594:	00000007 	udf	#7
	...
 5a0:	00010fc8 	.inst	0x00010fc8 ; undefined
 5a4:	00000000 	udf	#0
 5a8:	00000402 	udf	#1026
 5ac:	00000009 	udf	#9
	...

Disassembly of section .init:

00000000000005b8 <_init>:
 5b8:	d503201f 	nop
 5bc:	a9bf7bfd 	stp	x29, x30, [sp, #-16]!
 5c0:	910003fd 	mov	x29, sp
 5c4:	9400002c 	bl	674 <call_weak_fn>
 5c8:	a8c17bfd 	ldp	x29, x30, [sp], #16
 5cc:	d65f03c0 	ret

Disassembly of section .plt:

00000000000005d0 <.plt>:
 5d0:	a9bf7bf0 	stp	x16, x30, [sp, #-16]!
 5d4:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 5d8:	f947d211 	ldr	x17, [x16, #4000]
 5dc:	913e8210 	add	x16, x16, #0xfa0
 5e0:	d61f0220 	br	x17
 5e4:	d503201f 	nop
 5e8:	d503201f 	nop
 5ec:	d503201f 	nop

00000000000005f0 <__libc_start_main@plt>:
 5f0:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 5f4:	f947d611 	ldr	x17, [x16, #4008]
 5f8:	913ea210 	add	x16, x16, #0xfa8
 5fc:	d61f0220 	br	x17

0000000000000600 <__cxa_finalize@plt>:
 600:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 604:	f947da11 	ldr	x17, [x16, #4016]
 608:	913ec210 	add	x16, x16, #0xfb0
 60c:	d61f0220 	br	x17

0000000000000610 <__gmon_start__@plt>:
 610:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 614:	f947de11 	ldr	x17, [x16, #4024]
 618:	913ee210 	add	x16, x16, #0xfb8
 61c:	d61f0220 	br	x17

0000000000000620 <abort@plt>:
 620:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 624:	f947e211 	ldr	x17, [x16, #4032]
 628:	913f0210 	add	x16, x16, #0xfc0
 62c:	d61f0220 	br	x17

0000000000000630 <printf@plt>:
 630:	90000090 	adrp	x16, 10000 <__FRAME_END__+0xf708>
 634:	f947e611 	ldr	x17, [x16, #4040]
 638:	913f2210 	add	x16, x16, #0xfc8
 63c:	d61f0220 	br	x17

Disassembly of section .text:

0000000000000640 <_start>:
 640:	d503201f 	nop
 644:	d280001d 	mov	x29, #0x0                   	// #0
 648:	d280001e 	mov	x30, #0x0                   	// #0
 64c:	aa0003e5 	mov	x5, x0
 650:	f94003e1 	ldr	x1, [sp]
 654:	910023e2 	add	x2, sp, #0x8
 658:	910003e6 	mov	x6, sp
 65c:	90000080 	adrp	x0, 10000 <__FRAME_END__+0xf708>
 660:	f947f800 	ldr	x0, [x0, #4080]
 664:	d2800003 	mov	x3, #0x0                   	// #0
 668:	d2800004 	mov	x4, #0x0                   	// #0
 66c:	97ffffe1 	bl	5f0 <__libc_start_main@plt>
 670:	97ffffec 	bl	620 <abort@plt>

0000000000000674 <call_weak_fn>:
 674:	90000080 	adrp	x0, 10000 <__FRAME_END__+0xf708>
 678:	f947f400 	ldr	x0, [x0, #4072]
 67c:	b4000040 	cbz	x0, 684 <call_weak_fn+0x10>
 680:	17ffffe4 	b	610 <__gmon_start__@plt>
 684:	d65f03c0 	ret
 688:	d503201f 	nop
 68c:	d503201f 	nop

0000000000000690 <deregister_tm_clones>:
 690:	b0000080 	adrp	x0, 11000 <__data_start>
 694:	91004000 	add	x0, x0, #0x10
 698:	b0000081 	adrp	x1, 11000 <__data_start>
 69c:	91004021 	add	x1, x1, #0x10
 6a0:	eb00003f 	cmp	x1, x0
 6a4:	540000c0 	b.eq	6bc <deregister_tm_clones+0x2c>  // b.none
 6a8:	90000081 	adrp	x1, 10000 <__FRAME_END__+0xf708>
 6ac:	f947ec21 	ldr	x1, [x1, #4056]
 6b0:	b4000061 	cbz	x1, 6bc <deregister_tm_clones+0x2c>
 6b4:	aa0103f0 	mov	x16, x1
 6b8:	d61f0200 	br	x16
 6bc:	d65f03c0 	ret

00000000000006c0 <register_tm_clones>:
 6c0:	b0000080 	adrp	x0, 11000 <__data_start>
 6c4:	91004000 	add	x0, x0, #0x10
 6c8:	b0000081 	adrp	x1, 11000 <__data_start>
 6cc:	91004021 	add	x1, x1, #0x10
 6d0:	cb000021 	sub	x1, x1, x0
 6d4:	d37ffc22 	lsr	x2, x1, #63
 6d8:	8b810c41 	add	x1, x2, x1, asr #3
 6dc:	9341fc21 	asr	x1, x1, #1
 6e0:	b40000c1 	cbz	x1, 6f8 <register_tm_clones+0x38>
 6e4:	90000082 	adrp	x2, 10000 <__FRAME_END__+0xf708>
 6e8:	f947fc42 	ldr	x2, [x2, #4088]
 6ec:	b4000062 	cbz	x2, 6f8 <register_tm_clones+0x38>
 6f0:	aa0203f0 	mov	x16, x2
 6f4:	d61f0200 	br	x16
 6f8:	d65f03c0 	ret
 6fc:	d503201f 	nop

0000000000000700 <__do_global_dtors_aux>:
 700:	a9be7bfd 	stp	x29, x30, [sp, #-32]!
 704:	910003fd 	mov	x29, sp
 708:	f9000bf3 	str	x19, [sp, #16]
 70c:	b0000093 	adrp	x19, 11000 <__data_start>
 710:	39404260 	ldrb	w0, [x19, #16]
 714:	35000140 	cbnz	w0, 73c <__do_global_dtors_aux+0x3c>
 718:	90000080 	adrp	x0, 10000 <__FRAME_END__+0xf708>
 71c:	f947f000 	ldr	x0, [x0, #4064]
 720:	b4000080 	cbz	x0, 730 <__do_global_dtors_aux+0x30>
 724:	b0000080 	adrp	x0, 11000 <__data_start>
 728:	f9400400 	ldr	x0, [x0, #8]
 72c:	97ffffb5 	bl	600 <__cxa_finalize@plt>
 730:	97ffffd8 	bl	690 <deregister_tm_clones>
 734:	52800020 	mov	w0, #0x1                   	// #1
 738:	39004260 	strb	w0, [x19, #16]
 73c:	f9400bf3 	ldr	x19, [sp, #16]
 740:	a8c27bfd 	ldp	x29, x30, [sp], #32
 744:	d65f03c0 	ret
 748:	d503201f 	nop
 74c:	d503201f 	nop

0000000000000750 <frame_dummy>:
 750:	17ffffdc 	b	6c0 <register_tm_clones>

0000000000000754 <f>:
 754:	d10083ff 	sub	sp, sp, #0x20
 758:	b9000fe0 	str	w0, [sp, #12]
 75c:	b9000be1 	str	w1, [sp, #8]
 760:	b9001fff 	str	wzr, [sp, #28]
 764:	b9401fe1 	ldr	w1, [sp, #28]
 768:	b9400fe0 	ldr	w0, [sp, #12]
 76c:	0b000020 	add	w0, w1, w0
 770:	b9001fe0 	str	w0, [sp, #28]
 774:	b9401fe1 	ldr	w1, [sp, #28]
 778:	b9400be0 	ldr	w0, [sp, #8]
 77c:	0b000020 	add	w0, w1, w0
 780:	b9001fe0 	str	w0, [sp, #28]
 784:	b9401fe0 	ldr	w0, [sp, #28]
 788:	910083ff 	add	sp, sp, #0x20
 78c:	d65f03c0 	ret

0000000000000790 <main>:
 790:	a9be7bfd 	stp	x29, x30, [sp, #-32]!
 794:	910003fd 	mov	x29, sp
 798:	52801000 	mov	w0, #0x80                  	// #128
 79c:	b9001be0 	str	w0, [sp, #24]
 7a0:	52800800 	mov	w0, #0x40                  	// #64
 7a4:	b9001fe0 	str	w0, [sp, #28]
 7a8:	b9401fe1 	ldr	w1, [sp, #28]
 7ac:	b9401be0 	ldr	w0, [sp, #24]
 7b0:	97ffffe9 	bl	754 <f>
 7b4:	2a0003e1 	mov	w1, w0
 7b8:	90000000 	adrp	x0, 0 <__abi_tag-0x278>
 7bc:	911fc000 	add	x0, x0, #0x7f0
 7c0:	97ffff9c 	bl	630 <printf@plt>
 7c4:	52800000 	mov	w0, #0x0                   	// #0
 7c8:	a8c27bfd 	ldp	x29, x30, [sp], #32
 7cc:	d65f03c0 	ret

Disassembly of section .fini:

00000000000007d0 <_fini>:
 7d0:	d503201f 	nop
 7d4:	a9bf7bfd 	stp	x29, x30, [sp, #-16]!
 7d8:	910003fd 	mov	x29, sp
 7dc:	a8c17bfd 	ldp	x29, x30, [sp], #16
 7e0:	d65f03c0 	ret

Disassembly of section .rodata:

00000000000007e8 <_IO_stdin_used>:
 7e8:	00020001 	.inst	0x00020001 ; undefined
 7ec:	00000000 	udf	#0
 7f0:	000a6425 	.inst	0x000a6425 ; undefined

Disassembly of section .eh_frame_hdr:

00000000000007f4 <__GNU_EH_FRAME_HDR>:
 7f4:	3b031b01 	.inst	0x3b031b01 ; undefined
 7f8:	00000040 	udf	#64
 7fc:	00000007 	udf	#7
 800:	fffffe4c 	.inst	0xfffffe4c ; undefined
 804:	00000058 	udf	#88
 808:	fffffe9c 	.inst	0xfffffe9c ; undefined
 80c:	0000006c 	udf	#108
 810:	fffffecc 	.inst	0xfffffecc ; undefined
 814:	00000080 	udf	#128
 818:	ffffff0c 	.inst	0xffffff0c ; undefined
 81c:	00000094 	udf	#148
 820:	ffffff5c 	.inst	0xffffff5c ; undefined
 824:	000000b8 	udf	#184
 828:	ffffff60 	.inst	0xffffff60 ; undefined
 82c:	000000cc 	udf	#204
 830:	ffffff9c 	.inst	0xffffff9c ; undefined
 834:	000000e4 	udf	#228

Disassembly of section .eh_frame:

0000000000000838 <__FRAME_END__-0xc0>:
 838:	00000010 	udf	#16
 83c:	00000000 	udf	#0
 840:	00527a01 	.inst	0x00527a01 ; undefined
 844:	011e7804 	.inst	0x011e7804 ; undefined
 848:	001f0c1b 	.inst	0x001f0c1b ; undefined
 84c:	00000010 	udf	#16
 850:	00000018 	udf	#24
 854:	fffffdec 	.inst	0xfffffdec ; undefined
 858:	00000034 	udf	#52
 85c:	1e074100 	.inst	0x1e074100 ; undefined
 860:	00000010 	udf	#16
 864:	0000002c 	udf	#44
 868:	fffffe28 	.inst	0xfffffe28 ; undefined
 86c:	00000030 	udf	#48
 870:	00000000 	udf	#0
 874:	00000010 	udf	#16
 878:	00000040 	udf	#64
 87c:	fffffe44 	.inst	0xfffffe44 ; undefined
 880:	0000003c 	udf	#60
 884:	00000000 	udf	#0
 888:	00000020 	udf	#32
 88c:	00000054 	udf	#84
 890:	fffffe70 	.inst	0xfffffe70 ; undefined
 894:	00000048 	udf	#72
 898:	200e4100 	.inst	0x200e4100 ; undefined
 89c:	039e049d 	.inst	0x039e049d ; undefined
 8a0:	4e029342 	.inst	0x4e029342 ; undefined
 8a4:	0ed3ddde 	.inst	0x0ed3ddde ; undefined
 8a8:	00000000 	udf	#0
 8ac:	00000010 	udf	#16
 8b0:	00000078 	udf	#120
 8b4:	fffffe9c 	.inst	0xfffffe9c ; undefined
 8b8:	00000004 	udf	#4
 8bc:	00000000 	udf	#0
 8c0:	00000014 	udf	#20
 8c4:	0000008c 	udf	#140
 8c8:	fffffe8c 	.inst	0xfffffe8c ; undefined
 8cc:	0000003c 	udf	#60
 8d0:	200e4100 	.inst	0x200e4100 ; undefined
 8d4:	00000e4d 	udf	#3661
 8d8:	0000001c 	udf	#28
 8dc:	000000a4 	udf	#164
 8e0:	fffffeb0 	.inst	0xfffffeb0 ; undefined
 8e4:	00000040 	udf	#64
 8e8:	200e4100 	.inst	0x200e4100 ; undefined
 8ec:	039e049d 	.inst	0x039e049d ; undefined
 8f0:	0eddde4e 	.inst	0x0eddde4e ; undefined
 8f4:	00000000 	udf	#0

00000000000008f8 <__FRAME_END__>:
 8f8:	00000000 	udf	#0

Disassembly of section .init_array:

0000000000010d90 <__frame_dummy_init_array_entry>:
   10d90:	00000750 	udf	#1872
   10d94:	00000000 	udf	#0

Disassembly of section .fini_array:

0000000000010d98 <__do_global_dtors_aux_fini_array_entry>:
   10d98:	00000700 	udf	#1792
   10d9c:	00000000 	udf	#0

Disassembly of section .dynamic:

0000000000010da0 <.dynamic>:
   10da0:	00000001 	udf	#1
   10da4:	00000000 	udf	#0
   10da8:	0000002f 	udf	#47
   10dac:	00000000 	udf	#0
   10db0:	0000000c 	udf	#12
   10db4:	00000000 	udf	#0
   10db8:	000005b8 	udf	#1464
   10dbc:	00000000 	udf	#0
   10dc0:	0000000d 	udf	#13
   10dc4:	00000000 	udf	#0
   10dc8:	000007d0 	udf	#2000
   10dcc:	00000000 	udf	#0
   10dd0:	00000019 	udf	#25
   10dd4:	00000000 	udf	#0
   10dd8:	00010d90 	.inst	0x00010d90 ; undefined
   10ddc:	00000000 	udf	#0
   10de0:	0000001b 	udf	#27
   10de4:	00000000 	udf	#0
   10de8:	00000008 	udf	#8
   10dec:	00000000 	udf	#0
   10df0:	0000001a 	udf	#26
   10df4:	00000000 	udf	#0
   10df8:	00010d98 	.inst	0x00010d98 ; undefined
   10dfc:	00000000 	udf	#0
   10e00:	0000001c 	udf	#28
   10e04:	00000000 	udf	#0
   10e08:	00000008 	udf	#8
   10e0c:	00000000 	udf	#0
   10e10:	6ffffef5 	.inst	0x6ffffef5 ; undefined
   10e14:	00000000 	udf	#0
   10e18:	00000298 	udf	#664
   10e1c:	00000000 	udf	#0
   10e20:	00000005 	udf	#5
   10e24:	00000000 	udf	#0
   10e28:	000003a8 	udf	#936
   10e2c:	00000000 	udf	#0
   10e30:	00000006 	udf	#6
   10e34:	00000000 	udf	#0
   10e38:	000002b8 	udf	#696
   10e3c:	00000000 	udf	#0
   10e40:	0000000a 	udf	#10
   10e44:	00000000 	udf	#0
   10e48:	00000094 	udf	#148
   10e4c:	00000000 	udf	#0
   10e50:	0000000b 	udf	#11
   10e54:	00000000 	udf	#0
   10e58:	00000018 	udf	#24
   10e5c:	00000000 	udf	#0
   10e60:	00000015 	udf	#21
	...
   10e70:	00000003 	udf	#3
   10e74:	00000000 	udf	#0
   10e78:	00010f90 	.inst	0x00010f90 ; undefined
   10e7c:	00000000 	udf	#0
   10e80:	00000002 	udf	#2
   10e84:	00000000 	udf	#0
   10e88:	00000078 	udf	#120
   10e8c:	00000000 	udf	#0
   10e90:	00000014 	udf	#20
   10e94:	00000000 	udf	#0
   10e98:	00000007 	udf	#7
   10e9c:	00000000 	udf	#0
   10ea0:	00000017 	udf	#23
   10ea4:	00000000 	udf	#0
   10ea8:	00000540 	udf	#1344
   10eac:	00000000 	udf	#0
   10eb0:	00000007 	udf	#7
   10eb4:	00000000 	udf	#0
   10eb8:	00000480 	udf	#1152
   10ebc:	00000000 	udf	#0
   10ec0:	00000008 	udf	#8
   10ec4:	00000000 	udf	#0
   10ec8:	000000c0 	udf	#192
   10ecc:	00000000 	udf	#0
   10ed0:	00000009 	udf	#9
   10ed4:	00000000 	udf	#0
   10ed8:	00000018 	udf	#24
   10edc:	00000000 	udf	#0
   10ee0:	0000001e 	udf	#30
   10ee4:	00000000 	udf	#0
   10ee8:	00000008 	udf	#8
   10eec:	00000000 	udf	#0
   10ef0:	6ffffffb 	.inst	0x6ffffffb ; undefined
   10ef4:	00000000 	udf	#0
   10ef8:	08000001 	stxrb	w0, w1, [x0]
   10efc:	00000000 	udf	#0
   10f00:	6ffffffe 	.inst	0x6ffffffe ; undefined
   10f04:	00000000 	udf	#0
   10f08:	00000450 	udf	#1104
   10f0c:	00000000 	udf	#0
   10f10:	6fffffff 	.inst	0x6fffffff ; undefined
   10f14:	00000000 	udf	#0
   10f18:	00000001 	udf	#1
   10f1c:	00000000 	udf	#0
   10f20:	6ffffff0 	.inst	0x6ffffff0 ; undefined
   10f24:	00000000 	udf	#0
   10f28:	0000043c 	udf	#1084
   10f2c:	00000000 	udf	#0
   10f30:	6ffffff9 	.inst	0x6ffffff9 ; undefined
   10f34:	00000000 	udf	#0
   10f38:	00000004 	udf	#4
	...

Disassembly of section .got:

0000000000010f90 <.got>:
	...
   10fa8:	000005d0 	udf	#1488
   10fac:	00000000 	udf	#0
   10fb0:	000005d0 	udf	#1488
   10fb4:	00000000 	udf	#0
   10fb8:	000005d0 	udf	#1488
   10fbc:	00000000 	udf	#0
   10fc0:	000005d0 	udf	#1488
   10fc4:	00000000 	udf	#0
   10fc8:	000005d0 	udf	#1488
   10fcc:	00000000 	udf	#0
   10fd0:	00010da0 	.inst	0x00010da0 ; undefined
	...
   10ff0:	00000790 	udf	#1936
	...

Disassembly of section .data:

0000000000011000 <__data_start>:
	...

0000000000011008 <__dso_handle>:
   11008:	00011008 	.inst	0x00011008 ; undefined
   1100c:	00000000 	udf	#0

Disassembly of section .bss:

0000000000011010 <completed.0>:
	...

Disassembly of section .comment:

0000000000000000 <.comment>:
   0:	3a434347 	ccmn	w26, w3, #0x7, mi  // mi = first
   4:	62552820 	.inst	0x62552820 ; undefined
   8:	75746e75 	.inst	0x75746e75 ; undefined
   c:	2e313120 	usubw	v0.8h, v9.8h, v17.8b
  10:	2d302e34 	stp	s20, s11, [x17, #-128]
  14:	75627531 	.inst	0x75627531 ; undefined
  18:	3175746e 	adds	w14, w3, #0xd5d, lsl #12
  1c:	2e32327e 	usubw	v30.8h, v19.8h, v18.8b
  20:	20293430 	.inst	0x20293430 ; undefined
  24:	342e3131 	cbz	w17, 5c648 <__bss_end__+0x4b630>
  28:	Address 0x0000000000000028 is out of bounds.


Disassembly of section .debug_aranges:

0000000000000000 <.debug_aranges>:
   0:	0000002c 	udf	#44
   4:	00000002 	udf	#2
   8:	00080000 	.inst	0x00080000 ; undefined
   c:	00000000 	udf	#0
  10:	00000754 	udf	#1876
  14:	00000000 	udf	#0
  18:	0000007c 	udf	#124
	...

Disassembly of section .debug_info:

0000000000000000 <.debug_info>:
   0:	00000109 	udf	#265
   4:	08010005 	stxrb	w1, w5, [x0]
   8:	00000000 	udf	#0
   c:	00001204 	udf	#4612
  10:	00161d00 	.inst	0x00161d00 ; undefined
  14:	00000000 	udf	#0
  18:	07540000 	.inst	0x07540000 ; undefined
  1c:	00000000 	udf	#0
  20:	007c0000 	.inst	0x007c0000 ; undefined
	...
  2c:	08010000 	stxrb	w1, w0, [x0]
  30:	00000007 	udf	#7
  34:	05040500 	.inst	0x05040500 ; undefined
  38:	00746e69 	.inst	0x00746e69 ; undefined
  3c:	8e080101 	.inst	0x8e080101 ; undefined
  40:	01000000 	.inst	0x01000000 ; undefined
  44:	00aa0702 	.inst	0x00aa0702 ; undefined
  48:	04010000 	sub	z0.b, p0/m, z0.b, z0.b
  4c:	00000507 	udf	#1287
  50:	06010100 	.inst	0x06010100 ; undefined
  54:	00000090 	udf	#144
  58:	c4050201 	ld1sb	{z1.d}, p0/z, [x16, z5.d, uxtw]
  5c:	01000000 	.inst	0x01000000 ; undefined
  60:	00a10508 	.inst	0x00a10508 ; undefined
  64:	01010000 	.inst	0x01010000 ; undefined
  68:	00009708 	udf	#38664
  6c:	00660600 	.inst	0x00660600 ; undefined
  70:	bd070000 	str	s0, [x0, #1792]
  74:	02000000 	.inst	0x02000000 ; undefined
  78:	350c0164 	cbnz	w4, 180a4 <__bss_end__+0x708c>
  7c:	8a000000 	and	x0, x0, x0
  80:	08000000 	stxrb	w0, w0, [x0]
  84:	0000008a 	udf	#138
  88:	080a0009 	stxrb	w10, w9, [x0]
  8c:	0000006d 	udf	#109
  90:	00009c0b 	udf	#39947
  94:	05090100 	.inst	0x05090100 ; undefined
  98:	00000035 	udf	#53
  9c:	00000790 	udf	#1936
  a0:	00000000 	udf	#0
  a4:	00000040 	udf	#64
  a8:	00000000 	udf	#0
  ac:	00cb9c01 	.inst	0x00cb9c01 ; undefined
  b0:	61020000 	.inst	0x61020000 ; undefined
  b4:	35070a00 	cbnz	w0, e1f4 <__FRAME_END__+0xd8fc>
  b8:	02000000 	.inst	0x02000000 ; undefined
  bc:	62027891 	.inst	0x62027891 ; undefined
  c0:	35100a00 	cbnz	w0, 20200 <__bss_end__+0xf1e8>
  c4:	02000000 	.inst	0x02000000 ; undefined
  c8:	0c007c91 	st1	{v17.1d}, [x4]
  cc:	03010066 	.inst	0x03010066 ; undefined
  d0:	00003505 	udf	#13573
  d4:	00075400 	.inst	0x00075400 ; undefined
  d8:	00000000 	udf	#0
  dc:	00003c00 	udf	#15360
  e0:	00000000 	udf	#0
  e4:	039c0100 	.inst	0x039c0100 ; undefined
  e8:	350b0078 	cbnz	w24, 160f4 <__bss_end__+0x50dc>
  ec:	02000000 	.inst	0x02000000 ; undefined
  f0:	79036c91 	strh	w17, [x4, #438]
  f4:	00351200 	.inst	0x00351200 ; NYI
  f8:	91020000 	add	x0, x0, #0x80
  fc:	75730268 	.inst	0x75730268 ; undefined
 100:	0704006d 	.inst	0x0704006d ; undefined
 104:	00000035 	udf	#53
 108:	007c9102 	.inst	0x007c9102 ; undefined
	...

Disassembly of section .debug_abbrev:

0000000000000000 <.debug_abbrev>:
   0:	0b002401 	add	w1, w0, w0, lsl #9
   4:	030b3e0b 	.inst	0x030b3e0b ; undefined
   8:	0200000e 	.inst	0x0200000e ; undefined
   c:	08030034 	stxrb	w3, w20, [x1]
  10:	3b01213a 	.inst	0x3b01213a ; undefined
  14:	490b390b 	.inst	0x490b390b ; undefined
  18:	00180213 	.inst	0x00180213 ; undefined
  1c:	00050300 	.inst	0x00050300 ; undefined
  20:	213a0803 	.inst	0x213a0803 ; undefined
  24:	03213b01 	.inst	0x03213b01 ; undefined
  28:	13490b39 	.inst	0x13490b39 ; undefined
  2c:	00001802 	udf	#6146
  30:	25011104 	cmpge	p4.b, p4/z, z8.b, #1
  34:	030b130e 	.inst	0x030b130e ; undefined
  38:	111f1b1f 	add	wsp, w24, #0x7c6
  3c:	10071201 	adr	x1, e27c <__FRAME_END__+0xd984>
  40:	05000017 	orr	z23.s, z23.s, #0x1
  44:	0b0b0024 	add	w4, w1, w11
  48:	08030b3e 	stxrb	w3, w30, [x25]
  4c:	26060000 	.inst	0x26060000 ; undefined
  50:	00134900 	.inst	0x00134900 ; undefined
  54:	012e0700 	.inst	0x012e0700 ; undefined
  58:	0e03193f 	uzp1	v31.8b, v9.8b, v3.8b
  5c:	053b0b3a 	ext	z26.b, z26.b, z25.b, #218
  60:	19270b39 	.inst	0x19270b39 ; undefined
  64:	193c1349 	.inst	0x193c1349 ; undefined
  68:	00001301 	udf	#4865
  6c:	49000508 	.inst	0x49000508 ; undefined
  70:	09000013 	.inst	0x09000013 ; undefined
  74:	00000018 	udf	#24
  78:	0b000f0a 	add	w10, w24, w0, lsl #3
  7c:	0013490b 	.inst	0x0013490b ; undefined
  80:	012e0b00 	.inst	0x012e0b00 ; undefined
  84:	0e03193f 	uzp1	v31.8b, v9.8b, v3.8b
  88:	0b3b0b3a 	add	w26, w25, w27, uxtb #2
  8c:	13490b39 	.inst	0x13490b39 ; undefined
  90:	07120111 	.inst	0x07120111 ; undefined
  94:	197c1840 	.inst	0x197c1840 ; undefined
  98:	00001301 	udf	#4865
  9c:	3f012e0c 	.inst	0x3f012e0c ; undefined
  a0:	3a080319 	adcs	w25, w24, w8
  a4:	390b3b0b 	strb	w11, [x24, #718]
  a8:	4919270b 	.inst	0x4919270b ; undefined
  ac:	12011113 	and	w19, w8, #0x8000000f
  b0:	7a184007 	.inst	0x7a184007 ; undefined
  b4:	00000019 	udf	#25

Disassembly of section .debug_line:

0000000000000000 <.debug_line>:
   0:	0000006b 	udf	#107
   4:	00080005 	.inst	0x00080005 ; undefined
   8:	00000033 	udf	#51
   c:	fb010104 	.inst	0xfb010104 ; undefined
  10:	01000d0e 	.inst	0x01000d0e ; undefined
  14:	00010101 	.inst	0x00010101 ; undefined
  18:	00010000 	.inst	0x00010000 ; undefined
  1c:	01010100 	.inst	0x01010100 ; undefined
  20:	0000021f 	udf	#543
  24:	00230000 	.inst	0x00230000 ; NYI
  28:	01020000 	.inst	0x01020000 ; undefined
  2c:	030f021f 	.inst	0x030f021f ; undefined
  30:	00000016 	udf	#22
  34:	00001600 	udf	#5632
  38:	00300000 	.inst	0x00300000 ; NYI
  3c:	05010000 	orr	z0.s, z0.s, #0x1
  40:	02090014 	.inst	0x02090014 ; undefined
  44:	00000754 	udf	#1876
  48:	00000000 	udf	#0
  4c:	3d070514 	str	b20, [x8, #449]
  50:	0a054b21 	and	w1, w25, w5, lsl #18
  54:	2101054b 	.inst	0x2101054b ; undefined
  58:	052f0b05 	ext	z5.b, z5.b, z24.b, #122
  5c:	10052f07 	adr	x7, a63c <__FRAME_END__+0x9d44>
  60:	2f03052e 	mvni	v14.2s, #0x69
  64:	05750a05 	ext	z5.b, {z16.b, z17.b}, #170
  68:	02022101 	.inst	0x02022101 ; undefined
  6c:	Address 0x000000000000006c is out of bounds.


Disassembly of section .debug_str:

0000000000000000 <.debug_str>:
   0:	676e6f6c 	.inst	0x676e6f6c ; undefined
   4:	736e7520 	.inst	0x736e7520 ; undefined
   8:	656e6769 	fnmls	z9.h, p1/m, z27.h, z14.h
   c:	6e692064 	usubl2	v4.4s, v3.8h, v9.8h
  10:	4e470074 	.inst	0x4e470074 ; undefined
  14:	31432055 	adds	w21, w2, #0xc8, lsl #12
  18:	31312037 	adds	w23, w1, #0xc48
  1c:	302e342e 	adr	x14, 5c6a1 <__bss_end__+0x4b689>
  20:	6c6d2d20 	ldnp	d0, d11, [x9, #-304]
  24:	6c747469 	ldnp	d9, d29, [x3, #-192]
  28:	6e652d65 	uqsub	v5.8h, v11.8h, v5.8h
  2c:	6e616964 	fcvtxn2	v4.4s, v11.2d
  30:	616d2d20 	.inst	0x616d2d20 ; undefined
  34:	6c3d6962 	stnp	d2, d26, [x11, #-48]
  38:	20343670 	.inst	0x20343670 ; undefined
  3c:	2d20672d 	stp	s13, s25, [x25, #-256]
  40:	79736166 	ldrh	w6, [x11, #6576]
  44:	7268636e 	.inst	0x7268636e ; undefined
  48:	756f6e6f 	.inst	0x756f6e6f ; undefined
  4c:	6e752d73 	uqsub	v19.8h, v11.8h, v21.8h
  50:	646e6977 	.inst	0x646e6977 ; undefined
  54:	6261742d 	.inst	0x6261742d ; undefined
  58:	2073656c 	.inst	0x2073656c ; undefined
  5c:	7473662d 	.inst	0x7473662d ; undefined
  60:	2d6b6361 	ldp	s1, s24, [x27, #-168]
  64:	746f7270 	.inst	0x746f7270 ; undefined
  68:	6f746365 	umlsl2	v5.4s, v27.8h, v4.h[3]
  6c:	74732d72 	.inst	0x74732d72 ; undefined
  70:	676e6f72 	.inst	0x676e6f72 ; undefined
  74:	73662d20 	.inst	0x73662d20 ; undefined
  78:	6b636174 	.inst	0x6b636174 ; undefined
  7c:	616c632d 	.inst	0x616c632d ; undefined
  80:	702d6873 	adr	x19, 5ad8f <__bss_end__+0x49d77>
  84:	65746f72 	fnmls	z18.h, p3/m, z27.h, z20.h
  88:	6f697463 	uqshl	v3.2d, v3.2d, #41
  8c:	6e75006e 	uaddl2	v14.4s, v3.8h, v21.8h
  90:	6e676973 	.inst	0x6e676973 ; undefined
  94:	63206465 	.inst	0x63206465 ; undefined
  98:	00726168 	.inst	0x00726168 ; undefined
  9c:	6e69616d 	rsubhn2	v13.8h, v11.4s, v9.4s
  a0:	6e6f6c00 	umin	v0.8h, v0.8h, v15.8h
  a4:	6e692067 	usubl2	v7.4s, v3.8h, v9.8h
  a8:	68730074 	.inst	0x68730074 ; undefined
  ac:	2074726f 	.inst	0x2074726f ; undefined
  b0:	69736e75 	ldpsw	x21, x27, [x19, #-104]
  b4:	64656e67 	.inst	0x64656e67 ; undefined
  b8:	746e6920 	.inst	0x746e6920 ; undefined
  bc:	69727000 	ldpsw	x0, x28, [x0, #-112]
  c0:	0066746e 	.inst	0x0066746e ; undefined
  c4:	726f6873 	.inst	0x726f6873 ; undefined
  c8:	6e692074 	usubl2	v20.4s, v3.8h, v9.8h
  cc:	Address 0x00000000000000cc is out of bounds.


Disassembly of section .debug_line_str:

0000000000000000 <.debug_line_str>:
   0:	6d6f682f 	ldp	d15, d26, [x1, #-272]
   4:	69792f65 	ldpsw	x5, x11, [x27, #-56]
   8:	6f442f68 	.inst	0x6f442f68 ; undefined
   c:	656d7563 	fnmls	z3.h, p5/m, z11.h, z13.h
  10:	2f73746e 	.inst	0x2f73746e ; undefined
  14:	4c500043 	.inst	0x4c500043 ; undefined
  18:	52475941 	.inst	0x52475941 ; undefined
  1c:	444e554f 	smlslt	z15.h, z10.b, z14.b
  20:	2f00632e 	.inst	0x2f00632e ; undefined
  24:	2f727375 	fcmla	v21.4h, v27.4h, v18.h[1], #270
  28:	6c636e69 	ldnp	d9, d27, [x19, #-464]
  2c:	00656475 	.inst	0x00656475 ; undefined
  30:	69647473 	ldpsw	x19, x29, [x3, #-224]
  34:	00682e6f 	.inst	0x00682e6f ; undefined
```
