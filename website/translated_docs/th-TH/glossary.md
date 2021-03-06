---
id: glossary
title: Glossary
sidebar_label: Glossary
---

## Alexander

Testnet ตัวล่าสุดของ Polkadot

## บล็อก (Block)

สิ่งที่รวบรวมข้อมูลเช่นธุรกรรมที่บ่งบอกถึงการเปลี่ยนสถานะของบล็อกเชน

## เครื่องมือสำรวจบล็อก (Block Explorer)

แอปพลิเคชั่นที่ช่วยให้ผู้ใช้สำรวจข้อมูลของบล็อกต่าง ๆ บนบล็อกเชน

## BLS

ลายเซ็นดิจิตอล Boneh-Lynn-Shacham (BLS) มีการเซ็นที่ช้า การยืนยันที่ใช้เวลานาน ใช้ pairing-friendly curves ที่ช้าและปลอดภัยน้อยกว่า curve อื่นๆ และมีแนวโน้มที่จะอ่อนต่อการป้องกันอันตราย อย่างไรก็ตาม BLS มีตัวเลือก signature aggregation หลากหลายมากกว่า scheme ลายเซ็นอื่น ๆ ที่รู้จัก ซึ่งทำให้ BLS เป็น scheme ที่เหมาะสำหรับการลงคะแนนเสียงในอัลกอริธึมหาฉันทามติ และสำหรับ threshold signatures

## การเชื่อมต่อเครือข่าย (Bonding)

กระบวนการในการล็อกหรือ "แช่แข็ง" โทเค็นเพื่อแลกกับการเช่ือมต่อพาราเชนเข้ากับรีเลย์เชน กระบวนการนี้ทำให้มั่นใจได้ว่ามีเพียงเชนที่ถูกต้องและทำงานอยู่เท่านั้นที่จะสามารถเชื่อมเข้ากับรีเลย์เชนได้ เนื่องจากว่าถ้าไม่งั้นผู้ถือ DOT จะหยุดการล็อกโทเค็น

## สะพานเชื่อมต่อ (Bridge)

เป็นโหนดที่ทำหน้าที่เป็นตัวกลางระหว่างรีเลย์เชนบน Polkadot และบล็อกเชนภายนอก โดยทำให้บล็อกเชนภายนอกถูกมองเป็นพาราเชนโดยรีเลย์เชน (ตัวอย่างเช่น ทำให้เชนนอกรองรับ Polkadot Runtime Environment) สะพานเชื่อมต่อทำให้บล็อกเชนที่ไม่ถูกรองรับบน Polkadot เช่น Ethereum และ Bitcoin สามารถสื่อสารกับเครื่อข่าย Polkadot ได้

## Byzantine Fault Tolerance

คุณสมบัติของระบบที่สามารถทนต่อความผิดพลาดไบเซนไทน์ นั่นคือระบบที่ระบบย่อยสามารถล้มเหลวได้ แต่ไม่สามารถรู้ได้ชัดเจนว่าระบบย่อยบางระบบมีการล้มเหลวเกิดขึ้นหรือไม่ นี้หมายความว่าผู้สังเกตการณ์ที่แตกต่างกันในระบบไม่สามารถตัดสินใจร่วมกันได้ว่าระบบล้มเหลวหรือไม่ การที่มีคุณสมบัติ Byzantine fault tolerance เป็นส่วนสำคัญของการพัฒนาระบบกระจาย

## ผู้ตรวจทาน (Collator)

โหนดที่ทำหน้าที่ดูแลพาราเชนโดยการรวบรวมธุรกรรมบนพาราเชนและสร้างหลักฐานการเปลี่ยนสถานะให้ผู้ตรวจสอบ (Validator)

## ฉันทามติ (Consensus)

กระบวนการที่คนกลุ่มหนึ่งจะตกลงข้อมูลเฉพาะหนึ่งร่วมกัน (เช่นลำกับและองค์ประกอบของบล็อกบนบล็อกเชน) มีอัลกอริธึมที่หลากหลายที่ใช้สำหรับหาฉันทามติร่วมกัน อัลกอริทึมที่ใช้โดย Polkadot มีชื่อว่า GRANDPA

## DOTs

โทเค็นหลักของ Polkadot DOT มีจุดประสงค์สามประการ: การกำกับดูแลเครือข่าย (อนุญาตให้ผู้ถือโหวตเกี่ยวกับการอัพเกรดเครือข่ายและเหตุการณ์พิเศษอื่น ๆ) การดำเนินงานทั่วไป (ให้รางวัลผู้ที่ทำตัวดีและลงโทษผู้ที่ประพฤติตัวไม่ดี) และการเชื่อมต่อเครือข่าย (เชื่อมพาราเชนกับรีเลย์เชนโดยการล็อก DOT)

## Dapps

คําศัพท์ที่ใช้เรียกแอปพลิเคชันที่กระจายอำนาจ นั่นคือแอปซึ่งทำงานเป็นส่วนหนึ่งของเครือข่ายแบบกระจาย ซึ่งต่างจากการทำงานบนระบบหรือระบบชุดหนึ่ง

## Epoch

An epoch is a time duration in the BABE protocol that assigns leadership positions to authorities for production in slots. In Kusama, it is the same duration as a [session](#session).

## Era

A (whole) number of sessions, which is the period that the validator set (and each validator's active nominator set) is recalculated and where rewards are paid out.
## Equivocation

Providing conflicting information to the network. BABE equivocation entails creating multiple blocks in the same slot. GRANDPA equivocation would consist of signing multiple conflicting chains.

## Extrinsic

ฟังก์ชั่นที่ถูกกำหนดโดยโปรแกรมเมอร์ เช่นฟังก์ชั่นที่ไม่ได้ถูก built-in เข้ามาในเฟรมเวิร์ค สำหรับ Polkadot นี่หมายถึง binary blob ซึ่งแสดงถึงการเปลี่ยนสถานะ (state transition) บางอย่าง (เช่นการทำธุรกรรม) และถูกใช้ในพาราเชนเพื่อที่สื่อสารกับรีเลย์เชน

## การสรุปผล (Finality)

คุณสมบัติของบล็อกที่ไม่สามารถถูกย้อนกลับได้ โดยทั่วไปบล็อกที่สร้างขึ้นจะไม่ถูกสรุปผลว่าจะถูกเพิ่มเข้าบล็อกเชนหรือไม่จนกว่าจะถึงจุดหนึ่งในอนาคต - อาจจะไม่การเกิดขึ้นเลยก็เป็นได้ เหมือนในกรณีของ "probabilistic finality" ที่ใช้ใน Bitcoin (ถึงแม้ว่าบล็อกใน Bitcoin โดยทั่วไปจะถือว่าถูก "สรุปผล" หลังจากการยืนยันหกครั้ง เนื่องจากโอกาศที่บล็อกจะถูกย้อนกลับในจุดนั้นต่ำมาก) ในรีเลย์เชนของ Polkadot มีเป้าหมายที่จะทำการสรุปผลภายใน 10-12 วินาทีหลังจากถูกสร้าง

## เครื่องมือสรุปผล (Finality Gadget)

กลไกที่กำหนดผลสรุป

## ชาวประมง (Fisherman)

โหนดที่ทำหน้าที่ตรวจสอบการทำงานบนเครื่อข่ายของผู้ตรวจสอบ (Validator) และ ผู้ตรวจทาน (Collator) เพื่อหาพฤติกรรมผิดปกติ ชาวประมงจะต้องเดิมพัน DOT เล็กน้อยในการฟ้อง แต่จะได้รับรางวัลตอบแทนอย่างมากหากพบว่าพฤติกรรมไม่ดีจริง

## GRANDPA consensus algorithm

ย่อมากจาก GHOST-based Recursive Ancestor Deriving Prefix Agreement เป็นเครื่องมือสรุปผลของ Polkadot ซึ่งช่วยในการสรุปว่าบล็อกตัวไหนควรถูกเพิ่มเข้าบล็อกเชนอย่าง asynchronous สามารถอธิบายได้ และปลอดภัย สำหรับภาพรวมของ GRANDPA อ่านได้ที่โพสต์ Medium นี้: <https://medium.com/polkadot-network/polkadot-proof-of-concept-3-a-better-consensus-algorithm-e81c380a2372>

## การกำกับดูแล (Governance)

กระบวนการในการพิจารณาว่าการเปลี่ยนแปลงเครือข่ายใดบ้างควรได้รับอนุญาต เช่นการแก้ไขโค้ดหรือการเคลื่อนย้ายเงินทุน ระบบการกำกับดูแลใน Polkadot เป็นแบบ on-chain และใช้การลงคะแนนของผู้มีส่วนได้ส่วนเสียเป็นหลัก ซึ่งหมายความว่ากลุ่มผู้ถือหุ้น (DOTs) ส่วนใหญ่กำหนดทิศทางเติบโตของเครือข่าย

## สภาการกำกับดูแล (Governance Council)

กลุ่มออนไลน์บนบล็อกเชน ซึ่งประกอบด้วยบัญชีบล็อกเชนหลายบัญชี (เริ่มต้นที่ 6 จนถึง 24 บัญชี) ซึ่งทำหน้าที่เป็นตัวแทนของผู้มีส่วนได้เสียที่ไม่ลงคะแนนเสียง สมาชิกสภามีหน้าที่หลักสองประการ การเสนอ referenda เพื่อให้กลุ่มผู้มีส่วนได้เสียลงคะแนน และยกเลิก referenda ที่มีจุดประสงค์ร้าย

## KSM

อักษรย่อของโทเค็นบนเครือข่าย Kusama

## Kusama

The "canary network" for Polkadot. It consists of an early-release, unaudited version of the Polkadot software. It is not a testnet - after the transition to NPoS, the network is entirely in the hands of the community (i.e., Kusama token holders).

## LIBP2P

ไลบรารีโอเพนซอร์สสำหรับการสื่อสารแบบ P2P ที่มีการเข้ารหัสและฟังก์ชันเครือข่ายอื่น ๆ อ่านข้อมูลเพิ่มเติมได้ที่: [https://libp2p.io/](https://libp2p.io/)

## Liveness

คุณสมบัติของระบบกระจายที่บ่งบอกว่าในที่สุดระบบจะสามารถหาฉันทามติได้ ระบบที่ติดอยู่ในลูปไม่สิ้นสุด ถึงแม้ว่าจะมีการคำนวณเกิดขึ้น ไม่ถือว่ามี liveness ระบบที่ให้ผลลัพธ์ในที่สุด ถึงแม้ว่าจะไม่ถูกต้องหรือใช้เวลานาน ถือว่ามี liveness

## เครื่องมือสำรวจโหนด (Node Explorer)

เครื่องมือที่ให้ข้อมูลเกี่ยวกับโหนด เช่นบล็อกล่าสุดที่ถูกปิดผนึก บล็อกที่ถูกสรุป และสถานะบล็อกเชนปัจจุบัน

## Nominated Proof of Stake (NPoS)

ระบบ proof of stake ที่ผู้เสนอชื่อ (Nominators) ให้ยืมเงินที่ถูกล็อกเป็นหลักประกัน แก่ผู้ตรวจสอบ (Validators) เพราะเชื่อในในพฤติกรรมที่ดีของผู้ตรวจสอบ Nominated proof-of-stake แตกต่างจาก delegated proof-of-stake ตรงที่ ผู้เสนอช่ือ (Nominators) อาจสูญเสียเงินที่วางเป็นหลักประกันหากพวกเขาเสนอผู้ตรวจสอบที่ประพฤติตัวไม่ดี แต่ผู้แทน (Delegates) ไม่ต้องสูญเสียเงินเดิมพันตามพฤติกรรมของผู้ตรวจสอบ โปรดทราบว่าเทคโนโลยีบล็อกเชนอื่น ๆ อาจมีการใช้เรียกว่าเป็น delegated proof of stake ถึงแม้ว่าผู้แทนอาจจะถูกยึดหลักประกัน

## ผู้เสนอชื่อ (Nominator)

เป็นโหนดที่มีหน้าที่เลือกลุ่มผู้ตรวจชอบชุดนึง DOT จำนวนนึงต้องถูกล็อกเป็นหลักประกันเพื่อที่จะได้ทำหน้าที่ดังกล่าว ซึ่งอาจจะเกิดการสูญเสียของ DOT ได้หากผู้ตรวจสอบที่โหนดเลือกประพฤติตัวไม่ดี สิ่งนี้จึงบังคับให้ผู้เสนอชื่อเลือกผู้ตรวจสอบอย่างระมัดระวัง

## การกำกับดูบนบล็อกเชน (On-chain governance)

การกำกับดูแลของบล็อกเชน ซึ่งถูกควบคุมโดยกลไกที่ควบคุมโดยบล็อกเชน การกำกับดูแลแบบ On-chain ช่วยให้สามารถทำการตัดสินใจได้อย่างโปร่งใส โปรดทราบว่ามีอัลกอริทึมหลายตัวที่สามารถช่วยในการตัดสินใจเหล่านี้ เช่นการลงคะแนนเสียงข้างมาก และการลงคะแนนเสียงแบบ identity-based quadratic

## พาราเชน (Parachain)

เป็นบล็อกเชนที่มีคุณสมบัติหลายอย่างที่ทำให้สามารถทำงานบน Polkadot Runtime Environment ได้ อีกชื่อเรียกคือ "บล็อกเชนแบบขนาน"

## Parachain Registry

โครงสร้างคล้ายฐานข้อมูลที่ไม่ซับซ้อนที่เก็บข้อมูลทั้งแบบคงที่และแบบไดนามิกในแต่ละบล็อกเชน

## Parity Technologies

บริษัทที่ก่อตั้งโดย Dr. Gavin Wood ซึ่งกำลังพัฒนา Substrate บริษัทยังได้มีการพัฒนาโครงการอื่น ๆ อีกหลายอย่าง เช่น Parity Ethereum และ Parity Wasm

## Polkadot

เทคโนโลยีสำหรับหลายบล็อกเชนต่างชนิด ช่วยให้บล็อกเชนที่มีคุณลักษณะที่แตกต่างกันสามารถสื่อสารระหว่างกันได้

## Polkadot Runtime Environment

สภาวะแวดล้อมรันไทม์ (Runtime Environment) ที่โมดูลรันไทม์ (runtime module) สามารถรันบนได้ Parachains ต้องรองรับ Polkadot Runtime Environment - เครือข่ายภายนอกซึ่งไม่รองรับต้องใช้สะพานเชื่อมต่อ (Bridge) ในการเชื่อมต่อ

## Proof of Stake (PoS)

หนึ่งวิธีในการหาฉันทามติโดยกำหนดว่าบล็อกต่อไปจะถูกกำหนดโดยโหนดที่ถูกเลือกเพราะคุณสมบัติบางอย่าง (เช่น จำนวนโทเค็นที่วางเป็นหลักประกัน)

## Proof of Work

หนึ่งวิธีในการหาฉันทามติโดยกำหนดว่าบล็อกต่อไปคือบล็อกแรกที่สามารถแก้ไขปริศนาที่ยากได้ (เช่นใน Bitcoin ต้องหา pre-image hash เพื่อที่จะสร้างบล็อกต่อไป)

## ข้อเสนอ (Proposal)

การเรียกใช้ฟังก์ชันที่ต้องผ่านการลงคะแนนเสียงประชามติ ข้อเสนอมีสิทธิ์ในแก้ไขพฤติกรรมของเครือข่าย Polkadot ตั้งแต่การปรับพารามิเตอร์เล็กน้อยจนถึงการเปลี่ยนโค้ดรันไทม์

## การลงประชามติ (Referendum)

โหวตว่าข้อเสนอควรถูกเครือข่ายยอมรับหรือไม่ การลงประชามติอาจริเริ่มโดยสภาการกำกับดูแล (Governance Council) โดยสมาชิกของสาธารณชน หรือเป็นผลมาจากข้อเสนอก่อนหน้า ผู้มีส่วนได้ส่วนเสียลงคะแนนเสียง ซึ่งคิดตามจำนวน DOT ที่บัญชีผู้มีส่วนได้เสียควบคุมและระยะเวลาที่พวกเขาเต็มใจที่จะล็อค DOT ของพวกเขา

## รีเลย์เชน (Relay chain)

เชนที่มีหน้าที่ประสานงานแสวงหาฉันทามติ (consensus) และช่วยให้พาราเชนสื่อสารระหว่างกัน (และบล็อกเชนภายนอกผ่านสะพาน Bridge)

## Runtime

ฟังก์ชันการเปลี่ยนสถานะซึ่งระบุอัลกอริทึมสำหรับการกำหนดสถานะของบล็อกถัดไปโดยใช้ข้อมูลบล็อกก่อนหน้า

## Runtime Module

โค้ด Wasm ซึ่งเข้ารหัสฟังก์ชันการเปลี่ยนสถานะ

## ความปลอดภัย

คุณสมบัติของระบบแบบกระจายที่บ่งบอกถึงการตอบสนอง invariants ทั้งหมดอย่างถูกต้อง ซึ่งหมายความว่าจะไม่มีสิ่งใด "เลวร้าย" เกิดขึ้นกับข้อมูล (เช่นเกิดความเสียหาย)

## การปิดผนึก (Sealing)

กระบวนการเพิ่มบล็อกลงในรีเลย์เชน การสรุป (Finalization) ของบล็อกเป็นกระบวนการที่แยกจากกัน - บล็อกจะถูกสรุปหลังจากถูกปิดผนึกแล้วเท่านั้น (ประมาณ 10 - 12 วินาที)

## Session

เซสชั่นเป็นคำที่ใช้เรียกใน Substrate สำหรับระยะเวลาหนึ่งที่กลุ่มผู้ตรวจสอบคงที่ไม่สามารถมีการเปลี่ยนแปลง ผู้ตรวจสอบสามารถเข้าร่วมหรือออกจากกลุ่มผู้ตรวจสอบเมื่อมีการเปลี่ยนแปลงเซสชันเท่านั้น

## Session certificate

อีกชื่อเรียกของ Session "key" ซึ่งเป็นคีย์ประเภท BLS สำหรับ GRANDPA, sr25519 สำหรับ BABE และ Ed25519 สำหรับ libp2p.

## Session key

Session "key" เป็นคีย์ประเภท BLS สำหรับ GRANDPA, sr25519 สำหรับ BABE และ Ed25519 สำหรับ libp2p.

## Slashing

The removal of a percentage of an account's DOTs as a punishment for a validator acting maliciously or incompetently (e.g., equivocating or remaining offline for an extended period of time).

## การวางหลักประกัน (Staking)

การล็อกโทเค็น(DOTs ใน Polkadot) เพื่อเป็น "หลักประกัน" ในการขอโอกาสเป็นผู้สร้างบล็อกที่ถูกต้อง (และได้รับรางวัลจากการสร้างบล็อก) ผู้ตรวจสอบและผู้เสนอชื่อ (Nominators, ผู้ที่สนับสนุนผู้ตรวจสอบผ่าน NPoS) ร่วมกันวาง DOTs เป็นหลักประกันเพื่อเพิ่มบล็อกบนรีเลย์เชน

## ฟังก์ชั่นการเปลี่ยนสถานะ (State transition function)

ฟังก์ชั่นที่อธิบายถึงวิธีการเปลี่ยนสถานะของบล็อกเชน ตัวอย่างเช่นอาจอธิบายถึงวิธีการโอนโทเค็นจากบัญชีหนึ่งไปยังอีกบัญชีหนึ่ง

## Substrate

เฟรมเวิร์คที่ใช้ในการพัฒนา Polkadot Runtime Environment ซึ่งช่วยให้นักพัฒนาสามารถสร้างพาราเชน ซึ่งสามารถเชื่อมกับรีเลย์เชนของ Polkadot ได้

## Tabling

In Polkadot governance, bringing a proposal to a vote via referendum. Note that this is the British meaning of "tabling", which is different than the US version, which means "to postpone" a measure.

## ธุรกรรม (Transaction)

องค์ประกอบของฟังก์ชั่นการเปลี่ยนสถานะ (State Transition Function) ของแต่ละบล็อก เช่นการย้ายโทเค็นจากบัญชีหนึ่งไปยังอีกบัญชีหนึ่ง

## ผู้ตรวจสอบ (Validator)

โหนดที่ทำหน้าที่ดูแลความปลอดภัยของรีเลย์เชน (Relay Chain) โดยการตรวจสอบหลักฐานที่ได้จากผู้ตรวจทาน (Collators) ที่ทำงานบนพาราเชน และหาฉันทามติร่วมกันกับผู้ตรวจสอบท่านอื่น

## การลงคะแนนเสียง (Voting)

กระบวนการของผู้มีส่วนได้เสียที่จะตัดสินว่าข้อเสนอควรผ่านหรือไม่ คะแนนเสียงจะคิดตามจำนวน DOT ที่บัญชีผู้มีส่วนได้เสียควบคุมและระยะเวลาที่พวกเขาเต็มใจที่จะล็อค DOT ของพวกเขา การลงคะแนนอาจถูกแทนที่โดยสภาการกำกับดูแล (Governance Council) ถ้ามีข้อตกลงร่วมกันที่มีลักษณะเป็นการยอมรับแบบเอกฉันท์

## วอลเลต (Wallet)

โปรแกรมที่ทำให้ผู้ใช้สามารถเก็บ รับ และส่ง DOT หรือโทเค็นอื่น ๆ ที่ใช้เทคโนโลยีบล็อกเชน

## มูลนิธิ Web3

มูลนิธิที่ตั้งอยู่ในประเทศสวิตเซอร์แลนด์ ซึ่งมีจุดมุ่งหมายที่จะส่งเสริมและสนันสนุนการพัฒนาเทคโนโลยีและแอพพลิเคชั่นเกี่ยวโปรโตคอลซอฟต์แวร์เว็บแบบกระจายอำนาจ โดยเฉพาะโทคโนโลยีที่ใช้วิธีการเข้ารหัสลับที่ทันสมัยเพื่อช่วยเหลือในการกระจายอำนาจ เพื่อผลประโยชน์และเพื่อความมั่นคงของระบบนิเวศ Web3

## WebAssembly

WebAssembly หรือที่รู้จักในชื่อ Wasm เป็น Instruction format สำหรับ stack-based VM โมดูลรันไทม์ของ Polkadot ถูก compile เป็น Wasm

## Wasm

Instruction format สำหรับ stack-based VM โมดูลรันไทม์ของ Polkadot ถูก compile เป็น Wasm

## Witness

Cryptographic proof ที่ชี้แจงเกี่ยวกับความถูกต้องของข้อมูล
