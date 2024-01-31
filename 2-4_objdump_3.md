```c
yih@yih:~/Documents/C$ objdump -D -M intel -j .text PLAYGROUND --no-show-raw-insn

PLAYGROUND:     file format elf64-littleaarch64


Disassembly of section .text:

0000000000000640 <_start>:
 640:	objdump: unrecognised disassembler option: intel
nop
 644:	mov	x29, #0x0                   	// #0
 648:	mov	x30, #0x0                   	// #0
 64c:	mov	x5, x0
 650:	ldr	x1, [sp]
 654:	add	x2, sp, #0x8
 658:	mov	x6, sp
 65c:	adrp	x0, 10000 <__FRAME_END__+0xf708>
 660:	ldr	x0, [x0, #4080]
 664:	mov	x3, #0x0                   	// #0
 668:	mov	x4, #0x0                   	// #0
 66c:	bl	5f0 <__libc_start_main@plt>
 670:	bl	620 <abort@plt>

0000000000000674 <call_weak_fn>:
 674:	adrp	x0, 10000 <__FRAME_END__+0xf708>
 678:	ldr	x0, [x0, #4072]
 67c:	cbz	x0, 684 <call_weak_fn+0x10>
 680:	b	610 <__gmon_start__@plt>
 684:	ret
 688:	nop
 68c:	nop

0000000000000690 <deregister_tm_clones>:
 690:	adrp	x0, 11000 <__data_start>
 694:	add	x0, x0, #0x10
 698:	adrp	x1, 11000 <__data_start>
 69c:	add	x1, x1, #0x10
 6a0:	cmp	x1, x0
 6a4:	b.eq	6bc <deregister_tm_clones+0x2c>  // b.none
 6a8:	adrp	x1, 10000 <__FRAME_END__+0xf708>
 6ac:	ldr	x1, [x1, #4056]
 6b0:	cbz	x1, 6bc <deregister_tm_clones+0x2c>
 6b4:	mov	x16, x1
 6b8:	br	x16
 6bc:	ret

00000000000006c0 <register_tm_clones>:
 6c0:	adrp	x0, 11000 <__data_start>
 6c4:	add	x0, x0, #0x10
 6c8:	adrp	x1, 11000 <__data_start>
 6cc:	add	x1, x1, #0x10
 6d0:	sub	x1, x1, x0
 6d4:	lsr	x2, x1, #63
 6d8:	add	x1, x2, x1, asr #3
 6dc:	asr	x1, x1, #1
 6e0:	cbz	x1, 6f8 <register_tm_clones+0x38>
 6e4:	adrp	x2, 10000 <__FRAME_END__+0xf708>
 6e8:	ldr	x2, [x2, #4088]
 6ec:	cbz	x2, 6f8 <register_tm_clones+0x38>
 6f0:	mov	x16, x2
 6f4:	br	x16
 6f8:	ret
 6fc:	nop

0000000000000700 <__do_global_dtors_aux>:
 700:	stp	x29, x30, [sp, #-32]!
 704:	mov	x29, sp
 708:	str	x19, [sp, #16]
 70c:	adrp	x19, 11000 <__data_start>
 710:	ldrb	w0, [x19, #16]
 714:	cbnz	w0, 73c <__do_global_dtors_aux+0x3c>
 718:	adrp	x0, 10000 <__FRAME_END__+0xf708>
 71c:	ldr	x0, [x0, #4064]
 720:	cbz	x0, 730 <__do_global_dtors_aux+0x30>
 724:	adrp	x0, 11000 <__data_start>
 728:	ldr	x0, [x0, #8]
 72c:	bl	600 <__cxa_finalize@plt>
 730:	bl	690 <deregister_tm_clones>
 734:	mov	w0, #0x1                   	// #1
 738:	strb	w0, [x19, #16]
 73c:	ldr	x19, [sp, #16]
 740:	ldp	x29, x30, [sp], #32
 744:	ret
 748:	nop
 74c:	nop

0000000000000750 <frame_dummy>:
 750:	b	6c0 <register_tm_clones>

0000000000000754 <f>:
 754:	sub	sp, sp, #0x20
 758:	str	w0, [sp, #12]
 75c:	str	w1, [sp, #8]
 760:	str	wzr, [sp, #28]
 764:	ldr	w1, [sp, #28]
 768:	ldr	w0, [sp, #12]
 76c:	add	w0, w1, w0
 770:	str	w0, [sp, #28]
 774:	ldr	w1, [sp, #28]
 778:	ldr	w0, [sp, #8]
 77c:	add	w0, w1, w0
 780:	str	w0, [sp, #28]
 784:	ldr	w0, [sp, #28]
 788:	add	sp, sp, #0x20
 78c:	ret

0000000000000790 <main>:
 790:	stp	x29, x30, [sp, #-32]!
 794:	mov	x29, sp
 798:	mov	w0, #0x80                  	// #128
 79c:	str	w0, [sp, #24]
 7a0:	mov	w0, #0x40                  	// #64
 7a4:	str	w0, [sp, #28]
 7a8:	ldr	w1, [sp, #28]
 7ac:	ldr	w0, [sp, #24]
 7b0:	bl	754 <f>
 7b4:	mov	w1, w0
 7b8:	adrp	x0, 0 <__abi_tag-0x278>
 7bc:	add	x0, x0, #0x7f0
 7c0:	bl	630 <printf@plt>
 7c4:	mov	w0, #0x0                   	// #0
 7c8:	ldp	x29, x30, [sp], #32
 7cc:	ret

```
