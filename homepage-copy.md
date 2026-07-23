# AMRG — Homepage & Unit Copy
### Bilingual UI strings (EN / TH) for the homepage and unit framing
*Source of truth for the front-page text. Each entry has a `key`, an English string, and a Thai string. Keys match the site's string table so they can be dropped straight into code as input.*

---

## How to use
- Every item below is one UI string with two language values.
- `key` is the stable identifier. `en` and `th` are the display strings.
- Do not translate by re-typing; copy the exact strings — they are the reviewed, formal versions.
- Framing of the unit is **the management of professional practice throughout the building lifecycle**, not building law alone.
- English name: **Architectural Management Research Group (AMRG)**. Thai: **หน่วยวิจัยการจัดการงานสถาปัตยกรรม**. The unit is formally registered; "Research Group" is the chosen English rendering of หน่วยวิจัย.

---

## 1 · Hero — unit statement

**`home.h`** — main headline
- **EN:** Architectural management across the building lifecycle
- **TH:** การจัดการงานสถาปัตยกรรมตลอดอายุอาคาร

**`home.s`** — affiliation line
- **EN:** Architectural Management Research Group · Faculty of Architecture, Chulalongkorn University
- **TH:** หน่วยวิจัยการจัดการงานสถาปัตยกรรม · คณะสถาปัตยกรรมศาสตร์ จุฬาลงกรณ์มหาวิทยาลัย

**`home.subjectTag`** — subject-scope label (formerly "Building law")
- **EN:** A registered research unit of the Faculty
- **TH:** หน่วยวิจัยที่จัดตั้งอย่างเป็นทางการของคณะ

---

## 2 · Three domains (research · teaching · practice)

**`home.evT`** — section title
- **EN:** A single discipline across three domains
- **TH:** สาขาวิชาเดียว ครอบคลุมสามบทบาท

**`home.evS`** — section intro
- **EN:** The Group maintains an integrated relationship between research, teaching, and professional practice, as set out below.
- **TH:** หน่วยวิจัยดำเนินงานโดยเชื่อมโยงการวิจัย การเรียนการสอน และการปฏิบัติวิชาชีพเข้าด้วยกันอย่างเป็นระบบ ดังปรากฏต่อไปนี้

**`home.ev[0]`** — card 01
- **EN:** Research
- **TH:** การวิจัย

**`home.ev[1]`** — card 02
- **EN:** Teaching
- **TH:** การเรียนการสอน

**`home.ev[2]`** — card 03
- **EN:** Practice
- **TH:** การปฏิบัติวิชาชีพ

---

## 3 · Resources block

**`home.resT`** — title
- **EN:** Resources for practice
- **TH:** ทรัพยากรสำหรับการปฏิบัติงาน

**`home.resS`** — intro
- **EN:** Materials available for download and citation, prepared for those responsible for the procurement, costing, permitting, and inspection of buildings, in addition to the research community.
- **TH:** เอกสารสำหรับดาวน์โหลดและอ้างอิง จัดทำขึ้นสำหรับผู้ที่มีหน้าที่จัดจ้าง ประมาณราคา ขออนุญาต และตรวจสอบอาคาร ตลอดจนแวดวงวิชาการ

---

## 4 · Collaboration block

**`home.netT`** — title
- **EN:** Two decades of collaboration
- **TH:** ความร่วมมือกว่าสองทศวรรษ

**`home.netS`** — intro
- **EN:** The first memorandum of understanding was concluded in 2004. The Group maintains agreements with both the professional regulator and the professional association.
- **TH:** บันทึกความเข้าใจฉบับแรกจัดทำขึ้นเมื่อ พ.ศ. 2547 หน่วยวิจัยมีความร่วมมืออย่างเป็นทางการทั้งกับสภาวิชาชีพและสมาคมวิชาชีพ

---

## 5 · Shared label

**`home.all`** — "see all" link
- **EN:** See all
- **TH:** ดูทั้งหมด

---

## Compact reference table

| key | EN | TH |
|---|---|---|
| home.h | Architectural management across the building lifecycle | การจัดการงานสถาปัตยกรรมตลอดอายุอาคาร |
| home.s | Architectural Management Research Group · Faculty of Architecture, Chulalongkorn University | หน่วยวิจัยการจัดการงานสถาปัตยกรรม · คณะสถาปัตยกรรมศาสตร์ จุฬาลงกรณ์มหาวิทยาลัย |
| home.subjectTag | A registered research unit of the Faculty | หน่วยวิจัยที่จัดตั้งอย่างเป็นทางการของคณะ |
| home.evT | A single discipline across three domains | สาขาวิชาเดียว ครอบคลุมสามบทบาท |
| home.evS | The Group maintains an integrated relationship between research, teaching, and professional practice, as set out below. | หน่วยวิจัยดำเนินงานโดยเชื่อมโยงการวิจัย การเรียนการสอน และการปฏิบัติวิชาชีพเข้าด้วยกันอย่างเป็นระบบ ดังปรากฏต่อไปนี้ |
| home.ev[0] | Research | การวิจัย |
| home.ev[1] | Teaching | การเรียนการสอน |
| home.ev[2] | Practice | การปฏิบัติวิชาชีพ |
| home.resT | Resources for practice | ทรัพยากรสำหรับการปฏิบัติงาน |
| home.resS | Materials available for download and citation, prepared for those responsible for the procurement, costing, permitting, and inspection of buildings, in addition to the research community. | เอกสารสำหรับดาวน์โหลดและอ้างอิง จัดทำขึ้นสำหรับผู้ที่มีหน้าที่จัดจ้าง ประมาณราคา ขออนุญาต และตรวจสอบอาคาร ตลอดจนแวดวงวิชาการ |
| home.netT | Two decades of collaboration | ความร่วมมือกว่าสองทศวรรษ |
| home.netS | The first memorandum of understanding was concluded in 2004. The Group maintains agreements with both the professional regulator and the professional association. | บันทึกความเข้าใจฉบับแรกจัดทำขึ้นเมื่อ พ.ศ. 2547 หน่วยวิจัยมีความร่วมมืออย่างเป็นทางการทั้งกับสภาวิชาชีพและสมาคมวิชาชีพ |
| home.all | See all | ดูทั้งหมด |
