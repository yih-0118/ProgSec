```c
yih@yih:~/Documents/C$ objdump -D -M intel -j .text PLAYGROUND

PLAYGROUND:     file format elf64-littleaarch64


Disassembly of section .text:

0000000000000640 <_start>:
 640:	objdump: unrecognised disassembler option: intel
d503201f 	nop
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
```
