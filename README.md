# M456B Dual Mixdown Module · Routing

Ward-Beck Systems M456B, 1975|8. Wiki page: [M456B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M456B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 37 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 14 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 16 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 230 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 63 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1975 - M456B - P4.jpg](MANUALS/1975%20-%20M456B%20-%20P4.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | Adjustable from +5 dB to -5 dB _ t1 dB (fader fully open) _ ±0.25 dB from 20 Hz to 20 kHz. |
| **Noise** | 75 dB below nomina] output of -10 dBm (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.25% THD from 20 Hz to 20 kHz under the fo]owing conditions: |
| **Input** | +24 dBm Sensitivity: +8 dBm Fader: -15 dB Output: +6 dBm |
| **Source impedances** | 600 ohms maXimum, balanced |
| **Input impedances** | 30 000 ohms balanced (6,000 ohms with vu meter connected) |
| **Input levels** | 0 to +10 dBm nomina] +24 dBm maximum |
| **Output impedances** |  |
| &nbsp;&nbsp;Direct | SUMMING: Less than 200 ohms balanced _ 60,000 ohms or 30,000 ohms respectively, each output; balanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Direct | SUMMING 600 ohms minimum, balanced _ 5 ohms or Tess. |
| &nbsp;&nbsp;Output levels |  |
| &nbsp;&nbsp;Direct | SUMMING: -10 dBm nomina ] +20 dBm maximum _ Designed to produce -10 dBm at output of unity gain summing amplifier. |

## Circuit description

From [1975 - M456B - Dual Mixdown Module (2).pdf](MANUALS/1975%20-%20M456B%20-%20Dual%20Mixdown%20Module%20(2).pdf) pages 5-10 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**H4S6B DUAL HI XDOW N HODULE**

The H456B i s a dual channel unit designed tore cei ve either console (DIRECT) outputs o r tape (PLAYBACK) outputs. A solids tate switch selects the desired input source. The Ilod ule outputs feed a stereo 1l1xl ng bus which in turn supplies the feed forth eco nso le 1I0 nito ring sv s te s.

l!!.P.!!.! (Channel 11 described) Each channel is e q uf pped with. solid states witch ing circuit (Q3 through QB for Channel ' 1). This circuit operates in • two -p ol e double throw configuration.nd selects either the DIRECTor the PLAYBACK input for further processing. Int he 'nor.al' Ilode of operation, r. e. with p t n P2 -T oft he Ilod ul e connector not connected, the PLAYBACK input is switched ON and the DIRECT input iss witched OFF. When pin P2 -T is connected to ground potential, the status o f the two inputs is reversed. With the SYNC button SW8 depressed, the channel switching is assigned t o a separate control path forth e pu t-pe s e of selective sync or ov erd ub control. A separate cent ec t, perllit tinge x ter na l logic control via pin P2U, i s part of SIIB. The output of the solid states witch is followed by buffer up l 1f hrs Z1 and Z2. Z2 with QI O and Qll combined with Z3, Ql2 and Q13 for ll olin actively balanced output c i r cut t. Fro. here, the signal i s routed through the CHANNEl ON switch Sill and app ears at pins PI-2I / Y oft he Ilo du le connector. Mete ring Circuit Associated with each channel i s a ME!ter Select relay (KI). There lay picks off the signal ahead of thea udio solid state switches for the DIRECTor PLAYBACK inputs. ThE! lnE! tE!ri ng output appears at P2-9/K for HI.

OE! pending on the status of the relay, the metering c irc u t twill

bridge across either the DIRECTor the PlAYBACK input. As a

result, the meter circuit impedance will deter mine the input

impedance oft he channel being monitor e d.

WARC -BECK SYSTEMS LTC.

**&quot;4 56 B DUAL KIXDOW N MODULE**

Kl 15 operated by a transfstor d rfver cons t f ng o f QI and Q2. I t lIay be switched directly by applying a closure to the control COllllon potential at P2-P o r selectively via opera t ion oft he SYNC swftc h SWB a t P2R.

The.. ete rfng selection 15 fndependen t of the audio Input selection. With the aid of e x t erna l logic. t.h t s perllits the choice of a udfo and lIle teri n g functions independent o f one another. o r else ina follow 1I0de. whichever lIay bede sired.

Pins P I -2 I IY feed the input of a balanced fade r. The fader output 15 returned to the Ilodu l eat pins PII B/ V. A console lilly be equipped with twos f n g l e slide a t eenuaters occupy fng a sf ngle e e e ute space width. and thereby serving both channels of an K456B e e e ute.

Booster AMplifier Fro ll pins PI-18/V of the 1I0d u i e connector. the signal 15 brought dfrectly tot he input of one half of the 5-101 Booster A..plffi er. Th15 lI..p l iffe r operates at a galn of 15 dB andre covers the loss incur red when the fader isp Laced fn the nOll l na l 15 dB i nhand&quot; po s ft ion.

Outputs The output signal of the 5-101 a llpli f f e rfeeds the LEFT and RIGHT ee t n outputs via PANs witch SW3 and PAN control R85 through R89. I t alsop ro v f de s the feed forth e DIRECT out put. and. via SW2. forth e SOLO output. A separate contact on SW2 allows the opera t f ono f external solo log f c control c t r cut try.

Pr e h de REVERB SEND and FOLDBACI(outputs are made available wf t h separate level controls R68 through R71, followed by

ass fgn ment switches SW4, SW5, SW6 and S1I7.

All module outputs are controlled by the CHAnNEL ON s wftc h.

144568 DUAL Ki l DOW&quot; MODULE

I!!.!.n.!!.tl..

The second che nne I of the 144568 operates ina lIan ne r t dent t ce t t o che nne t 11 as described above.

The DIRECT outputs o f the two..adu le cheln nels are brought out indhi duelll y. for all other outputs. the two c nanne rs a r-e COJl'l b l ned Into single outputs. Intended t o be connected tot he appropriate console.. ixing buses.

Power Supply Decoup l ing Powers upp l y deco up lf ng isp r c v t ce u by CR9, CRI D, R100 through RIOSa nd e1 9 through e 22.

RI 0 2 and RI0 3 d e couple the supply voltage and reduce i t to tl 8 volts too per e t e 2 1 through 26.

**PARTS LIST**

PART DESCRIPTION HFG MFG PART NUMBER CI Capa~1 tor 2Z uF/ 2 5 V Philips 426ETFZZ 02 4.7 ~F/lO V K e ~e t Tl90B475MOIOAS

0.02Z uF

**0.1 ~F/35 V**

Aselce Ke~et

**CQ9Z-MC-213M**

Tl90A124M03SAS

ClO 33 uF/lO V 1 390 0336M0 10&quot; S Cl 1 C12 6.8 eF Ph!lips Z222 -6~8-09688 Cl 3

14 4 7 pF 0.01 uF As e1ce

**CQ9Z-MC-I03M**

Cl6 6.8 pF Philips 2ZZZ-638-09688 Cl7 220 ~ F /l O V K e~et 1390F2~7MO 10AS Cl 8 Cl9 22 u ~ / 2 5 y Ph!li ps 426ETF22

C24 4.7 ~F/lO V Ke ~ e t 1390B475MOIOAS

02 8 0.0 22 uF as etc c CQ92-MC-223 M C29 0.1 ~ F /3 5 V Ke~e t 1 390Al0 4M0 35AS 0 0

'32 33 u ~/lD V T 39 D D J ~6M OI OAS

'34 ef

6.8 Ph lips Z 2 22-6 ~ 8 -09 6 8 B

**PARTS LIST**

&quot; 4 568 DUAL &quot;IX DOIlN MODULE

PART DESCRIPTION MFG MFG PART NUM8ER

C36 Capa ~l tor 47 pF Phll ip s 2 22 2-6 38-70 479 C37 0.0 1 uF As e lc:o CQ92 -KCI03M C38 6.8pF Philips 2222 -638 -09688 C39 220 ~F /l O y Kelllet T39 0 F2 27 MOI OAS

CRt Diode Motor o h I H40 0 3 CR2 Fa l r c:hl1 d I N41 48

CR9 Hotoro h I N40 0 3

**CRIO**

CRll CR12 Fa irch il d I N41 48

**CR20**

LED, cod

051 FL!1l 7

S i;lIlen s V2~O I2 -AO I05 -AOO I &quot;&quot; Rel a!

W AFl C -B ECK SYSTEMS LTC.

**H4 56B DUAL HIXDOWN HOOULE**

PART DESCRIPTION &quot;FG HFG PART HUMBER

~~ Tran ~ ls tor ZNZI 0 2

**PH3569**

Q3 S F~8 0 4 1

Q' 2H440 1 Ql0 Fai rc hil d 2H356 9 QlI 2H3645 Q12 2N3569 Q13 2N3645 Q14 2N2 102 Q15 PN3569 ere SF~804 1

Q22 2H4401 Q23 2H356 9 Q24 2N3645 Q25 2N3569 Q26 2N3645

'1 R es i ~ tor.v

**R6 22K**

R7 m

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNDRVZGsxbDdicVk/view?resourcekey=0-EJf4buKZAgvpo22XV-aFog" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNDRVZGsxbDdicVk&resourcekey=0-EJf4buKZAgvpo22XV-aFog" width="240" alt="1975 - M456B - 456-04-009 - ENG DUAL MIXDOWN MODULE.jpg"></a><br><sub>1975|8 · 456-04-009 - ENG DUAL MIXDOWN MODULE · <a href="MECHANICAL/1975%20-%20M456B%20-%20456-04-009%20-%20ENG%20DUAL%20MIXDOWN%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV1lFMlIzZTQza0E/view?resourcekey=0-Crl57c8KJM3gcx8TFrEVwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV1lFMlIzZTQza0E&resourcekey=0-Crl57c8KJM3gcx8TFrEVwQ" width="240" alt="1975 - M456B - 456-04-009 - SWITCH SWI WHEN DEPRESSED ACTIVATES CHANNE OUTPUT CIRCUITS.jpg"></a><br><sub>1975|8 · 456-04-009 - SWITCH SWI WHEN DEPRESSED ACTIVATES CHANNE OUTPUT CIRCUITS · <a href="MECHANICAL/1975%20-%20M456B%20-%20456-04-009%20-%20SWITCH%20SWI%20WHEN%20DEPRESSED%20ACTIVATES%20CHANNE%20OUTPUT%20CIRCUITS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazZxdFoxUVEyLVU/view?resourcekey=0-XqdYVh7q7ck5aeguhJ6NJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazZxdFoxUVEyLVU&resourcekey=0-XqdYVh7q7ck5aeguhJ6NJg" width="240" alt="1975 - M456B - 481-03-015 - DUAL BOOSTER AMPLIFIER.jpg"></a><br><sub>1975|8 · 481-03-015 - DUAL BOOSTER AMPLIFIER · <a href="MECHANICAL/1975%20-%20M456B%20-%20481-03-015%20-%20DUAL%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M456B.stl`](MECHANICAL/M456B.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M456B)

- **Size:** 68.44 × 425.54 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 21 holes and cut-outs, 2 knobs (front panel: `MECHANICAL/M456B - front panel.svg`)
- the drawn panel is 0.11 wide to high, the size 0.16: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M456B.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHluM29XbU1CN2c/view?resourcekey=0-LHvbbrsB1XD27oQ8RaexPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHluM29XbU1CN2c&resourcekey=0-LHvbbrsB1XD27oQ8RaexPQ" width="240" alt="1975 - M456B - 456-01-003 - SOLO CONTROL COMMON (2).jpg"></a><br><sub>1975|8 · 456-01-003 - SOLO CONTROL COMMON (2) · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-01-003%20-%20SOLO%20CONTROL%20COMMON%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1R6YnIwbTloVFU/view?resourcekey=0-iQAGxj39xgE_AnNp8r0znQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1R6YnIwbTloVFU&resourcekey=0-iQAGxj39xgE_AnNp8r0znQ" width="240" alt="1975 - M456B - 456-01-003 - SOLO CONTROL COMMON.jpg"></a><br><sub>1975|8 · 456-01-003 - SOLO CONTROL COMMON · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-01-003%20-%20SOLO%20CONTROL%20COMMON%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWUYzQ3JQU2RhT2c/view?resourcekey=0-NIEU4QGAWebC5fMPgjhYMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWUYzQ3JQU2RhT2c&resourcekey=0-NIEU4QGAWebC5fMPgjhYMw" width="240" alt="1975 - M456B - 456-02-003 - PI-H SWIA RIES.jpg"></a><br><sub>1975|8 · 456-02-003 - PI-H SWIA RIES · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-02-003%20-%20PI-H%20SWIA%20RIES%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbk1pYjVqSFVfTW8/view?resourcekey=0-vCev3lgoLpWMcs7dBMmbsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbk1pYjVqSFVfTW8&resourcekey=0-vCev3lgoLpWMcs7dBMmbsg" width="240" alt="1975 - M456B - 456-02-003 - YUD YZX.jpg"></a><br><sub>1975|8 · 456-02-003 - YUD YZX · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-02-003%20-%20YUD%20YZX%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaElpcGJzTVppUVk/view?resourcekey=0-OgWSbzY1KQrXZalEZHJjUA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaElpcGJzTVppUVk&resourcekey=0-OgWSbzY1KQrXZalEZHJjUA" width="240" alt="1975 - M456B - 456-06-001 - COMPONENT SIDE NOTES RESISTORS RGO.jpg"></a><br><sub>1975|8 · 456-06-001 - COMPONENT SIDE NOTES RESISTORS RGO · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-06-001%20-%20COMPONENT%20SIDE%20NOTES%20RESISTORS%20RGO%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVFVUUNNQ29PRUU/view?resourcekey=0-3dUHlb7hga70QegvH6x-fQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVFVUUNNQ29PRUU&resourcekey=0-3dUHlb7hga70QegvH6x-fQ" width="240" alt="1975 - M456B - 456-06-001 - DUAL MIXDOWN MODULE.jpg"></a><br><sub>1975|8 · 456-06-001 - DUAL MIXDOWN MODULE · <a href="SCHEMATICS/1975%20-%20M456B%20-%20456-06-001%20-%20DUAL%20MIXDOWN%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTlN0ajcwdHRfU3c/view?resourcekey=0-5GsJciQgOdfI-c9kbpTpAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTlN0ajcwdHRfU3c&resourcekey=0-5GsJciQgOdfI-c9kbpTpAA" width="240" alt="1975 - M456B - 5-101-02-001 - MOD ICKD USED.jpg"></a><br><sub>1975|8 · 5-101-02-001 - MOD ICKD USED · <a href="SCHEMATICS/1975%20-%20M456B%20-%205-101-02-001%20-%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdm1PRzlvZG5pdmM/view?resourcekey=0-8B6REmnlxjZgrQtk0cu9Aw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdm1PRzlvZG5pdmM&resourcekey=0-8B6REmnlxjZgrQtk0cu9Aw" width="240" alt="1975 - M456B - 5-101-06-001.jpg"></a><br><sub>1975|8 · 5-101-06-001 · <a href="SCHEMATICS/1975%20-%20M456B%20-%205-101-06-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWmpkVjBUQjFwYjA/view?resourcekey=0-6nkTAb1CQ6nlUDyW_MHxZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWmpkVjBUQjFwYjA&resourcekey=0-6nkTAb1CQ6nlUDyW_MHxZg" width="240" alt="1975 - M456B - 5_101-02-001 - BLACK COM ISSMODICKD USEDON.jpg"></a><br><sub>1975|8 · 5_101-02-001 - BLACK COM ISSMODICKD USEDON · <a href="SCHEMATICS/1975%20-%20M456B%20-%205_101-02-001%20-%20BLACK%20COM%20ISSMODICKD%20USEDON%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVTFNcUdSaVhYUWM/view?resourcekey=0-bcaJpX4YQ36x9kS3R9ufHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVTFNcUdSaVhYUWM&resourcekey=0-bcaJpX4YQ36x9kS3R9ufHA" width="240" alt="1975 - M456B - 456-04-006 - DUAL MIXDOWN MODULE CONNECTOR REAR VIEW.jpg"></a><br><sub>1975|8 · 456-04-006 - DUAL MIXDOWN MODULE CONNECTOR REAR VIEW · <a href="PINOUTS/1975%20-%20M456B%20-%20456-04-006%20-%20DUAL%20MIXDOWN%20MODULE%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU0ZUaWxaQ1o2a1k/view?resourcekey=0-n8Zht8E0EbQOrSkST1QHYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU0ZUaWxaQ1o2a1k&resourcekey=0-n8Zht8E0EbQOrSkST1QHYA" width="240" alt="1975 - M456B - 456-04-006 - XDOWN MODULE CONNECTOR REAR VIEW.jpg"></a><br><sub>1975|8 · 456-04-006 - XDOWN MODULE CONNECTOR REAR VIEW · <a href="PINOUTS/1975%20-%20M456B%20-%20456-04-006%20-%20XDOWN%20MODULE%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M456B - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 2 pinout pictures (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | MON OUT 4 | out | MON OUT 4 | high |
| P1-2 | MON OUT 3 | out | MON OUT 3 | high |
| P1-3 | MON OUT 2 | out | MON OUT 2 | high |
| P1-4 | MON OUT 1 | out | MON OUT 1 | high |
| P1-5 | RS2 BUS | bus | RS2 | high |
| P1-6 | RS1 BUS | bus | RS1 | high |
| P1-7 | FB2 BUS | bus | FB2 | high |
| P1-8 | FB1 BUS | bus | FB1 | high |
| P1-9 | SOLO BUS | bus | SOLO | high |
| P1-10 | SHIELD | shield |  | high |
| P1-11 | N/C | nc |  | high |
| P1-12 | N/C | nc |  | high |
| P1-13 | N/C | nc |  | high |
| P1-14 | N/C | nc |  | high |
| P1-15 | CH1 DIRECT OUT | out | CH1 DIR OUT | high |
| P1-16 | CH2 DIRECT OUT | out | CH2 DIR OUT | high |
| P1-17 | N/C | nc |  | high |
| P1-18 | CH1 BOOST IN | in | CH1 BOOST IN | high |
| P1-19 | CH2 BOOST IN | in | CH2 BOOST IN | high |
| P1-20 | SHIELD | shield |  | high |
| P1-21 | CH1 PRE OUT | out | CH1 PRE OUT | high |
| P1-22 | CH2 PRE OUT | out | CH2 PRE OUT | high |
| P1-A | MON OUT 4 | out | MON OUT 4 | high |
| P1-B | MON OUT 3 | out | MON OUT 3 | high |
| P1-C | MON OUT 2 | out | MON OUT 2 | high |
| P1-D | MON OUT 1 | out | MON OUT 1 | high |
| P1-E | RS2 BUS | bus | RS2 | high |
| P1-F | RS1 BUS | bus | RS1 | high |
| P1-H | FB2 BUS | bus | FB2 | high |
| P1-J | FB1 BUS | bus | FB1 | high |
| P1-K | SOLO BUS | bus | SOLO | high |
| P1-L | SHIELD | shield |  | high |
| P1-M | N/C | nc |  | high |
| P1-N | N/C | nc |  | high |
| P1-P | N/C | nc |  | high |
| P1-R | N/C | nc |  | high |
| P1-S | CH1 DIRECT OUT | out | CH1 DIR OUT | high |
| P1-T | CH2 DIRECT OUT | out | CH2 DIR OUT | high |
| P1-U | N/C | nc |  | high |
| P1-V | CH1 BOOST IN | in | CH1 BOOST IN | high |
| P1-W | CH2 BOOST IN | in | CH2 BOOST IN | high |
| P1-X | SHIELD | shield |  | high |
| P1-Y | CH1 PRE OUT | out | CH1 PRE OUT | high |
| P1-Z | CH2 PRE OUT | out | CH2 PRE OUT | high |
| P2-1 | CH1 DIRECT IN | in | CH1 DIR IN | high |
| P2-2 | CH1 PLAYBACK IN | in | CH1 PB IN | high |
| P2-3 | N/C | nc |  | high |
| P2-4 | N/C | nc |  | high |
| P2-5 | CH2 DIRECT IN | in | CH2 DIR IN | high |
| P2-6 | CH2 PLAYBACK IN | in | CH2 PB IN | high |
| P2-7 | N/C | nc |  | high |
| P2-8 | N/C | nc |  | high |
| P2-9 | VU1 | out | VU1 | high |
| P2-10 | VU2 | out | VU2 | high |
| P2-11 | N/C | nc |  | high |
| P2-12 | N/C | nc |  | high |
| P2-13 | VU2 SELECT | control_in | VU2 SELECT | high |
| P2-14 | VU2 SYNC | control_in | VU2 SYNC | high |
| P2-15 | CH2 SELECT CONTROL | control_in | CH2 SEL CTL | high |
| P2-16 | CH2 SYNC | control_in | CH2 SYNC | high |
| P2-17 | CH2 EXT CONTROL | control_in | CH2 EXT CTL | high |
| P2-18 | CONTROL COMMON | ground |  | high |
| P2-19 | -25 V | power |  | high |
| P2-20 | 25 V COMMON | ground |  | high |
| P2-21 | +25 V | power |  | high |
| P2-22 | CHASSIS | ground |  | high |
| P2-A | CH1 DIRECT IN | in | CH1 DIR IN | high |
| P2-B | CH1 PLAYBACK IN | in | CH1 PB IN | high |
| P2-C | N/C | nc |  | high |
| P2-D | N/C | nc |  | high |
| P2-E | CH2 DIRECT IN | in | CH2 DIR IN | high |
| P2-F | CH2 PLAYBACK IN | in | CH2 PB IN | high |
| P2-H | N/C | nc |  | high |
| P2-J | N/C | nc |  | high |
| P2-K | VU1 | out | VU1 | high |
| P2-L | VU2 | out | VU2 | high |
| P2-M | N/C | nc |  | high |
| P2-N | N/C | nc |  | high |
| P2-P | VU1 SELECT | control_in | VU1 SELECT | high |
| P2-R | VU1 SYNC | control_in | VU1 SYNC | high |
| P2-S | CH1 SELECT CONTROL | control_in | CH1 SEL CTL | high |
| P2-T | CH1 SYNC | control_in | CH1 SYNC | high |
| P2-U | CH1 EXT CONTROL | control_in | CH1 EXT CTL | high |
| P2-V | SOLO CONTROL | control_in | SOLO CTL | high |
| P2-W | N/C | nc |  | high |
| P2-X | N/C | nc |  | high |
| P2-Y | +24 V | power |  | high |
| P2-Z | N/C | nc |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU1ZFMzJTb0pJWkE/view?resourcekey=0-I0cR8T8pJhNQyBOqRT5nTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU1ZFMzJTb0pJWkE&resourcekey=0-I0cR8T8pJhNQyBOqRT5nTg" width="240" alt="1975 - M456B - Dual Mixdown Module (2).pdf"></a><br><sub>1975|8 · Dual Mixdown Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlpfVUFWZDQzeE0/view?resourcekey=0-xq83xr80i4DlOHHruYiI0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlpfVUFWZDQzeE0&resourcekey=0-xq83xr80i4DlOHHruYiI0A" width="240" alt="1975 - M456B - Dual Mixdown Module.pdf"></a><br><sub>1975|8 · Dual Mixdown Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDNtT3ZJWHpGdm8/view?resourcekey=0-lQcXC8P6Jdtk9yUTFpB8IQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDNtT3ZJWHpGdm8&resourcekey=0-lQcXC8P6Jdtk9yUTFpB8IQ" width="240" alt="1975 - M456B - P001 - Title Page.jpg"></a><br><sub>1975|8 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEQ1WGRrNDZQdmM/view?resourcekey=0-6PAQ3bxtJh-zdgjju0lctg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEQ1WGRrNDZQdmM&resourcekey=0-6PAQ3bxtJh-zdgjju0lctg" width="240" alt="1975 - M456B - P003 - 1-1.jpg"></a><br><sub>1975|8 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ1RHU001X0RkcEE/view?resourcekey=0-EyQyg5M6WpoGJTLSj5-XQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ1RHU001X0RkcEE&resourcekey=0-EyQyg5M6WpoGJTLSj5-XQg" width="240" alt="1975 - M456B - P004 - 1-2.jpg"></a><br><sub>1975|8 · P004 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMUhFS21QTFZuWEU/view?resourcekey=0-3wpbFXmfTrcQ6TCxDG4NZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMUhFS21QTFZuWEU&resourcekey=0-3wpbFXmfTrcQ6TCxDG4NZg" width="240" alt="1975 - M456B - P005 - 2-1.jpg"></a><br><sub>1975|8 · P005 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlRRUFdVTUNYdEU/view?resourcekey=0-sbE3PCT0wEhXWLQrbwsg3A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlRRUFdVTUNYdEU&resourcekey=0-sbE3PCT0wEhXWLQrbwsg3A" width="240" alt="1975 - M456B - P006 - 2-2.jpg"></a><br><sub>1975|8 · P006 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcDVJYzBFeEpYYU0/view?resourcekey=0-SuRDsv9r3tf7_Z-1xAk11A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcDVJYzBFeEpYYU0&resourcekey=0-SuRDsv9r3tf7_Z-1xAk11A" width="240" alt="1975 - M456B - P007 - 2-3.jpg"></a><br><sub>1975|8 · P007 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU9qRmh3bGlKdFk/view?resourcekey=0-mu5wERyW1Nwdp5nJJCjtDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU9qRmh3bGlKdFk&resourcekey=0-mu5wERyW1Nwdp5nJJCjtDQ" width="240" alt="1975 - M456B - P008 - 3-1.jpg"></a><br><sub>1975|8 · P008 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKelJ2bV9iWUZTTEk/view?resourcekey=0-fN-KZ1hSkoKTXjjyA4DBzA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKelJ2bV9iWUZTTEk&resourcekey=0-fN-KZ1hSkoKTXjjyA4DBzA" width="240" alt="1975 - M456B - P009 - 3-2.jpg"></a><br><sub>1975|8 · P009 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWENZaDRYVkZNanM/view?resourcekey=0-nbtwEFwvBszLXE3lxVn0aQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWENZaDRYVkZNanM&resourcekey=0-nbtwEFwvBszLXE3lxVn0aQ" width="240" alt="1975 - M456B - P010 - 3-3.jpg"></a><br><sub>1975|8 · P010 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFhSVVBObGNuMTA/view?resourcekey=0-58aqzQsQ3Ky4jmFBgeKjFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFhSVVBObGNuMTA&resourcekey=0-58aqzQsQ3Ky4jmFBgeKjFg" width="240" alt="1975 - M456B - P011 - 3-4.jpg"></a><br><sub>1975|8 · P011 - 3-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1oxU1VtS2Q4MXc/view?resourcekey=0-jjgintXUVqFC3iOCOPaKMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1oxU1VtS2Q4MXc&resourcekey=0-jjgintXUVqFC3iOCOPaKMg" width="240" alt="1975 - M456B - P012 - 3-5.jpg"></a><br><sub>1975|8 · P012 - 3-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVVDZEIwdDdSZmc/view?resourcekey=0-OBs_p4a5tXJ0QxlpOIIjag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVVDZEIwdDdSZmc&resourcekey=0-OBs_p4a5tXJ0QxlpOIIjag" width="240" alt="1975 - M456B - P013 - 3-6.jpg"></a><br><sub>1975|8 · P013 - 3-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUxzS1o4V2t5LWM/view?resourcekey=0-8PPbBKVhgOnsD_YO26bsHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUxzS1o4V2t5LWM&resourcekey=0-8PPbBKVhgOnsD_YO26bsHQ" width="240" alt="1975 - M456B - P014 - 3-7.jpg"></a><br><sub>1975|8 · P014 - 3-7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOE1SUF9hMEI3LUU/view?resourcekey=0-iFTnCnn_HBLNy5IenuNPBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOE1SUF9hMEI3LUU&resourcekey=0-iFTnCnn_HBLNy5IenuNPBg" width="240" alt="1975 - M456B - P015 - 3-8.jpg"></a><br><sub>1975|8 · P015 - 3-8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2JiX3BpWkRfMXM/view?resourcekey=0-ERlYl_xSRyM95k6aebonBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2JiX3BpWkRfMXM&resourcekey=0-ERlYl_xSRyM95k6aebonBA" width="240" alt="1975 - M456B - P016 - 3-9.jpg"></a><br><sub>1975|8 · P016 - 3-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZEZERVhDWk1JMkU/view?resourcekey=0-GEWpnk52pNzNU8-l53-uig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZEZERVhDWk1JMkU&resourcekey=0-GEWpnk52pNzNU8-l53-uig" width="240" alt="1975 - M456B - P017 - 3-10.jpg"></a><br><sub>1975|8 · P017 - 3-10</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYThMOHRSZFBIZ2M/view?resourcekey=0-onPOO2sYIa40XzMXPuheUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYThMOHRSZFBIZ2M&resourcekey=0-onPOO2sYIa40XzMXPuheUg" width="240" alt="1975 - M456B - P018 - 5-101.jpg"></a><br><sub>1975|8 · P018 - 5-101</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0JvVmRfTGtVM3M/view?resourcekey=0-OuGZnDTTrrCH1lpuI66HaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0JvVmRfTGtVM3M&resourcekey=0-OuGZnDTTrrCH1lpuI66HaQ" width="240" alt="1975 - M456B - P019 - 5-101-1-1.jpg"></a><br><sub>1975|8 · P019 - 5-101-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG9sT25EcnZZajQ/view?resourcekey=0-a8cJgQzvNfIzwpsa7BOG0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG9sT25EcnZZajQ&resourcekey=0-a8cJgQzvNfIzwpsa7BOG0g" width="240" alt="1975 - M456B - P020 - 5-101-1-2.jpg"></a><br><sub>1975|8 · P020 - 5-101-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3Ixd2JMVDg4dGs/view?resourcekey=0-VTdTgj2-84XKNuovzsdgvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3Ixd2JMVDg4dGs&resourcekey=0-VTdTgj2-84XKNuovzsdgvg" width="240" alt="1975 - M456B - P021 - 5-101-2-1.jpg"></a><br><sub>1975|8 · P021 - 5-101-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWdBWTVEeWpCWFE/view?resourcekey=0-_nPeDO1qvGw7krDukgCEaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWdBWTVEeWpCWFE&resourcekey=0-_nPeDO1qvGw7krDukgCEaQ" width="240" alt="1975 - M456B - P022 - 5-101-2-2.jpg"></a><br><sub>1975|8 · P022 - 5-101-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN0xSX1JOTDBMYVE/view?resourcekey=0-GmJAwkgNrMikOaZl50xqjQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN0xSX1JOTDBMYVE&resourcekey=0-GmJAwkgNrMikOaZl50xqjQ" width="240" alt="1975 - M456B - P023 - 5-101-2-3.jpg"></a><br><sub>1975|8 · P023 - 5-101-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbmMwS2pnZU9mT2M/view?resourcekey=0-Ch44HVO9ReB1uykNrj5fLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbmMwS2pnZU9mT2M&resourcekey=0-Ch44HVO9ReB1uykNrj5fLA" width="240" alt="1975 - M456B - P1.jpg"></a><br><sub>1975|8 · P1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWmx0cE5Tc0tzZFU/view?resourcekey=0-HefnOhNLJtZ6AA8f0C-Tmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWmx0cE5Tc0tzZFU&resourcekey=0-HefnOhNLJtZ6AA8f0C-Tmw" width="240" alt="1975 - M456B - P10.jpg"></a><br><sub>1975|8 · P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU1VJU0luRUk2aEk/view?resourcekey=0-ymluaczDmRReoZp5D26RFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU1VJU0luRUk2aEk&resourcekey=0-ymluaczDmRReoZp5D26RFQ" width="240" alt="1975 - M456B - P11.jpg"></a><br><sub>1975|8 · P11</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNC01R2Z0WkloZ28/view?resourcekey=0-Ht11Em_29NG6HktrXkOUOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNC01R2Z0WkloZ28&resourcekey=0-Ht11Em_29NG6HktrXkOUOA" width="240" alt="1975 - M456B - P12.jpg"></a><br><sub>1975|8 · P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDRaUGlEaThPMmc/view?resourcekey=0-W_UAwgt4YyUaE0mco-5WhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDRaUGlEaThPMmc&resourcekey=0-W_UAwgt4YyUaE0mco-5WhA" width="240" alt="1975 - M456B - P13.jpg"></a><br><sub>1975|8 · P13</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRmdyZ053bGo4UVU/view?resourcekey=0-hXhujtRAGjt6U2Zy1GZBJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRmdyZ053bGo4UVU&resourcekey=0-hXhujtRAGjt6U2Zy1GZBJg" width="240" alt="1975 - M456B - P14.jpg"></a><br><sub>1975|8 · P14</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFU0bW5TREc5MFk/view?resourcekey=0-f6D1Bm6n5dj2M6vQLmZjYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFU0bW5TREc5MFk&resourcekey=0-f6D1Bm6n5dj2M6vQLmZjYw" width="240" alt="1975 - M456B - P15.jpg"></a><br><sub>1975|8 · P15</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnFDRXduQXhwSTA/view?resourcekey=0-I4HH7M_s42J6VoKMlaVY_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnFDRXduQXhwSTA&resourcekey=0-I4HH7M_s42J6VoKMlaVY_Q" width="240" alt="1975 - M456B - P16.jpg"></a><br><sub>1975|8 · P16</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOWVvTUloNzZqNFU/view?resourcekey=0-9RFxpwJVEF4YZxOJZUv47w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOWVvTUloNzZqNFU&resourcekey=0-9RFxpwJVEF4YZxOJZUv47w" width="240" alt="1975 - M456B - P17.jpg"></a><br><sub>1975|8 · P17</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUlhVMVNCeE1keUE/view?resourcekey=0-8YHhb8T1Cl_Fdxh_c-N35Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUlhVMVNCeE1keUE&resourcekey=0-8YHhb8T1Cl_Fdxh_c-N35Q" width="240" alt="1975 - M456B - P18.jpg"></a><br><sub>1975|8 · P18</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZk1nNlhsLXlHT2M/view?resourcekey=0-mMJ13iWRplXPoLAmqOGBNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZk1nNlhsLXlHT2M&resourcekey=0-mMJ13iWRplXPoLAmqOGBNQ" width="240" alt="1975 - M456B - P19.jpg"></a><br><sub>1975|8 · P19</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTQ5YU5SZEdhNmM/view?resourcekey=0-x6j8gJ7LK727g6TnI1efuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTQ5YU5SZEdhNmM&resourcekey=0-x6j8gJ7LK727g6TnI1efuQ" width="240" alt="1975 - M456B - P20.jpg"></a><br><sub>1975|8 · P20</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUM2MkVWVHdycUU/view?resourcekey=0-vjmQ9WzX6DxTrXAxx81yKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUM2MkVWVHdycUU&resourcekey=0-vjmQ9WzX6DxTrXAxx81yKg" width="240" alt="1975 - M456B - P21.jpg"></a><br><sub>1975|8 · P21</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzVqbnlYbHIxWFk/view?resourcekey=0-jez8pGwK67vKSd5mdFTphg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzVqbnlYbHIxWFk&resourcekey=0-jez8pGwK67vKSd5mdFTphg" width="240" alt="1975 - M456B - P22.jpg"></a><br><sub>1975|8 · P22</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM19wRDdNa3VSWjA/view?resourcekey=0-b1MKLpDatJqGoKbFhG0b9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM19wRDdNa3VSWjA&resourcekey=0-b1MKLpDatJqGoKbFhG0b9g" width="240" alt="1975 - M456B - P23.jpg"></a><br><sub>1975|8 · P23</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNXBuUXZuQTFkeE0/view?resourcekey=0-6F7WuCNibASxtGTqVvskvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNXBuUXZuQTFkeE0&resourcekey=0-6F7WuCNibASxtGTqVvskvg" width="240" alt="1975 - M456B - P24.jpg"></a><br><sub>1975|8 · P24</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2stU0VLQ1VSWkE/view?resourcekey=0-wA86lgjHHOA90vN-HGYGrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2stU0VLQ1VSWkE&resourcekey=0-wA86lgjHHOA90vN-HGYGrA" width="240" alt="1975 - M456B - P3.jpg"></a><br><sub>1975|8 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2thaDZuZDJPeEE/view?resourcekey=0-h2FV6xLU6SKoCmX3EmOaoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2thaDZuZDJPeEE&resourcekey=0-h2FV6xLU6SKoCmX3EmOaoQ" width="240" alt="1975 - M456B - P4.jpg"></a><br><sub>1975|8 · P4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG9wZWZzZERSRzA/view?resourcekey=0-fxM8khbH2itaqgDNily3tg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG9wZWZzZERSRzA&resourcekey=0-fxM8khbH2itaqgDNily3tg" width="240" alt="1975 - M456B - P5.jpg"></a><br><sub>1975|8 · P5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0VJS0k5LWdsYjQ/view?resourcekey=0-1IcsMsmFRFfQRNfsAp61pg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0VJS0k5LWdsYjQ&resourcekey=0-1IcsMsmFRFfQRNfsAp61pg" width="240" alt="1975 - M456B - P6.jpg"></a><br><sub>1975|8 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2hwVDJTbGx2b00/view?resourcekey=0-psrPQ34RO9feLAu5aB2STQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2hwVDJTbGx2b00&resourcekey=0-psrPQ34RO9feLAu5aB2STQ" width="240" alt="1975 - M456B - P7.jpg"></a><br><sub>1975|8 · P7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNDUwanEtRmswd3M/view?resourcekey=0-shpUhWCqN8IWhMdLucZSbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNDUwanEtRmswd3M&resourcekey=0-shpUhWCqN8IWhMdLucZSbw" width="240" alt="1975 - M456B - P8.jpg"></a><br><sub>1975|8 · P8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUy1sQnlnTm9jNGM/view?resourcekey=0-KDK8V-7cJbVri2sSp-AFPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUy1sQnlnTm9jNGM&resourcekey=0-KDK8V-7cJbVri2sSp-AFPA" width="240" alt="1975 - M456B - P9.jpg"></a><br><sub>1975|8 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaXV5aHV4OUFkZG8/view?resourcekey=0-BMnBCJm1F9IplKGWpbrUSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaXV5aHV4OUFkZG8&resourcekey=0-BMnBCJm1F9IplKGWpbrUSw" width="240" alt="1978 - M456B - P002.jpg"></a><br><sub>1978|11 · P002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGcxWFgxM2RkLVk/view?resourcekey=0-Dat2XnLe3Om8KLvwIHYotw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGcxWFgxM2RkLVk&resourcekey=0-Dat2XnLe3Om8KLvwIHYotw" width="240" alt="1978 - M456B - P2.jpg"></a><br><sub>1978|11 · P2</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1975 - M456B - 456-01-003 - SOLO CONTROL COMMON (2).kicad_sch](KICAD/1975%20-%20M456B%20-%20456-01-003%20-%20SOLO%20CONTROL%20COMMON%20(2).kicad_sch)
- [1975 - M456B - 456-01-003 - SOLO CONTROL COMMON.kicad_sch](KICAD/1975%20-%20M456B%20-%20456-01-003%20-%20SOLO%20CONTROL%20COMMON.kicad_sch)
- [1975 - M456B - 456-02-003 - PI-H SWIA RIES.kicad_sch](KICAD/1975%20-%20M456B%20-%20456-02-003%20-%20PI-H%20SWIA%20RIES.kicad_sch)
- [1975 - M456B - 456-02-003 - YUD YZX.kicad_sch](KICAD/1975%20-%20M456B%20-%20456-02-003%20-%20YUD%20YZX.kicad_sch)
- [1975 - M456B - 5-101-02-001 - MOD ICKD USED.kicad_sch](KICAD/1975%20-%20M456B%20-%205-101-02-001%20-%20MOD%20ICKD%20USED.kicad_sch)
- [1975 - M456B - 5_101-02-001 - BLACK COM ISSMODICKD USEDON.kicad_sch](KICAD/1975%20-%20M456B%20-%205_101-02-001%20-%20BLACK%20COM%20ISSMODICKD%20USEDON.kicad_sch)
- [1975 - M456B - Dual Mixdown Module (2) p25.kicad_sch](KICAD/1975%20-%20M456B%20-%20Dual%20Mixdown%20Module%20(2)%20p25.kicad_sch)
- [1975 - M456B - Dual Mixdown Module p25.kicad_sch](KICAD/1975%20-%20M456B%20-%20Dual%20Mixdown%20Module%20p25.kicad_sch)
- [1975 - M456B - Dual Mixdown Module p29.kicad_sch](KICAD/1975%20-%20M456B%20-%20Dual%20Mixdown%20Module%20p29.kicad_sch)
- [M456B.kicad_sym](KICAD/M456B.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
