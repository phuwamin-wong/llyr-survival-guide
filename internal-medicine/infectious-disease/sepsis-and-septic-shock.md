---
description: พิศิษฐ์
icon: face-eyes-xmarks
---

# Sepsis and Septic Shock

### Definition (คำจำกัดความ)

* Sepsis: สงสัยว่ามี Infection ร่วมกับ Organ failure ประเมินโดย SOFA score
* Probable Sepsis: ภาวะที่สงสัยการติดเชื้อรุนแรง แต่ยังไม่ครบเกณฑ์การวินิจฉัย Sepsis
* Sepsis-induced Hypotension (SIH): Sepsis ร่วมกับ MAP < 65 mmHg
* Septic Shock: ภาวะ SIH ที่ไม่ตอบสนองต่อสารน้ำ ต้องใช้ยากระตุ้นความดัน (Vasopressors) และ มีค่า Lactate > 2 mmol/L

#### สิ่งที่ต้องถามกลับเมื่อได้รับแจ้ง (What to ask back?)

พยาบาลมักจะแจ้งอาการเช่น ไข้สูง, BP drop, ซึมลง, หรือ O₂ saturation drop

* Vital Signs ล่าสุดทั้งหมด โดยเฉพาะ BP, Heart Rate

***

### Patient Evaluation & Initial Management

Flow การทำงานอ้างอิงจาก CMU 2022 และปรับปรุงตาม Surviving Sepsis Campaign (SSC) 2026 และ Thai Guidelines 2026

#### 🚨 Step 0: Look for the Cause of Shock

* หากผู้ป่วยมาด้วยภาวะช็อก อย่าลืมมองหาสาเหตุอื่นของช็อก ร่วมด้วย (เช่น Hypovolemic, Cardiogenic, หรือ Obstructive shock) ก่อนที่จะสรุปว่าเป็น Septic shock เพียงอย่างเดียว

#### 🌬️ Step 1: Initial Support (ABC)

* 1.1 Airway & Breathing (AB):
  * ประเมิน Patent airway และคำนวณ NEWS score
  * O₂ Support: ไทย 2026 แนะนำ keep SpO<sub>2</sub> 88-94% _(อย่างไรก็ตาม ในทางปฏิบัติควรปรึกษาแพทย์รุ่นพี่ เนื่องจากบางท่านอาจยังแนะนำให้ >94%)_
  * High Flow O₂: ตามไทย/SSC 2026 หากต้องใช้ High flow แนะนำใช้ HHHFNC มากกว่า NIV เพื่อลดภาวะปอดอักเสบจากการใช้เครื่องช่วยหายใจ (p-SILI)
  * _อย่าลืมเจาะ POCT-glucose (ตรวจน้ำตาลในเลือด) เพื่อประเมิน Hypoglycemia เสมอ_
* 1.2 Circulation (C) - Fluid Resuscitation:
  * หาก MAP < 65 mmHg ให้เริ่มสารน้ำเบื้องต้น
  * สารน้ำที่แนะนำ: Balanced Crystalloid (เช่น Acetar, Ringer's Lactate)
  * Thai Guideline 2026:
    * เริ่ม Load สารน้ำทีละ 10 ml/kg (ใช้ Ideal Body Weight) ภายใน 30 นาที
    * ประเมิน Volume responsiveness ซ้ำ (US IVC, Pulse Pressure Variation - PPV)
    * ไม่ควรให้เกิน 30 ml/kg ภายใน 3 ชั่วโมง
    * _ข้อควรระวัง:_ ให้น้อยๆ และระวังในผู้ป่วยที่มีภาวะน้ำเกิน (Volume overload), Capillary leakage, ESRD, Heart Failure และหาก BMI > 30 ให้ใช้ Adjusted Body Weight

#### 🔬 Step 2: Hx, PE & Septic Workup

* ซักประวัติ (Hx) และตรวจร่างกาย (PE) หาสาเหตุ (Source) ของ Sepsis ตามแนวทาง "Approach Fever"

{% content-ref url="fever.md" %}
[fever.md](fever.md)
{% endcontent-ref %}

* Lab Septic Workup:
  * SOFA Labs: CBC, BUN, Cr, LFT, Coagulation, +/- ABG
  * Lactate (สำคัญมาก)
  * Hemoculture (H/C) x 2 และเก็บ Specimen จาก Source ที่สงสัย (ต้องเก็บก่อนให้ ATB)

#### 💉 Step 3: Hemodynamic Resuscitation (Vasopressors)

* 3.1 Early Vasopressors:
  * Norepinephrine (NE): (เช่น 4-8 mg + D5W 250 ml, เริ่มที่ 0.05 mcg/kg/min)
  * Thai 2026: สามารถเริ่มให้ IV NE ได้เลยแต่เนิ่นๆ โดยเฉพาะในรายที่ช็อกรุนแรง, DBP < 45 mmHg, Diastolic Shock Index > 3, หรือในกลุ่มผู้ป่วยที่มีภาวะน้ำเกิน
  * _(หมายเหตุ: ไทยยังยอมรับให้ Dopamine เป็น 1st line ได้ในกรณีที่มีภาวะ Bradycardia (Slow PR) หรือ Poor LVEF)_
* 3.2 Hemodynamic Targets:
  * Macrocirculation: MAP $$≥$$ 65 mmHg (หรือสูงกว่านี้ในผู้ป่วยที่มีประวัติ Hypertension)
    * _SSC 2026 อนุโลมให้ผู้ป่วยสูงอายุ (Elderly) keep MAP ที่ 60-65 mmHg ได้_
  * Microcirculation: Lactate < 2 mmol/L, Capillary Refill Time (CRT) < 2 วินาที, ผู้ป่วยไม่ตัวเย็น (No cold extremities) หรือตัวลาย (No mottling)

#### 💊 Step 4: Antibiotics (ATB)

* 4.1 Timing of ATB:
  * SSC 2026 & ไทย 2026 Strong Recommendation: ต้องให้ ATB ภายใน 1 ชั่วโมง โดยคลุมเชื้อตาม Source ที่สงสัยและประเมินความเสี่ยงต่อเชื้อดื้อยา (MDR risk) ทั้งในผู้ป่วยที่มีภาวะช็อกและไม่ช็อก
  * _(SSC 2026 ปรับลดความน่าเชื่อถือของการรอให้ยาภายใน 3 ชั่วโมงในผู้ป่วยไม่ช็อก เป็นเพียง Conditional recommendation)_
  * เมื่อทราบผลเพาะเชื้อ ต้องรีบปรับยาให้แคบลง (De-escalate) อย่างรวดเร็ว
* 4.2 Mode of Administration:
  * สำหรับยากลุ่ม Beta-lactam, SSC 2026 แนะนำให้บริหารยาแบบ Prolonged Infusion จะได้ผลดีกว่าแบบ Loading

***

### Further Management

#### 🩸 Step 5: Albumin / Plasma Consideration

* Thai 2026: พิจารณาให้ Albumin/Plasma ได้ หากได้รับสารน้ำ Crystalloid เกิน 50 ml/kg แล้วความดันยังไม่ขึ้น
* SSC 2026: ไม่แนะนำให้ใช้ (Not recommended) เป็นทางเลือกแรก

#### 🚨 Step 6: Refractory Shock Management

เมื่อได้รับยา NE ในขนาด > 0.25 mcg/kg/min แต่ MAP ยังไม่ถึงเป้าหมาย ให้ดำเนินการตาม 3 ขั้นตอน:

* 6.1 หาสาเหตุและแก้ไข: ตรวจสอบและรักษาภาวะ Hypocalcemia (Vasoplegia), Hypovolemia, หรือ Severe Metabolic Acidosis
* 6.2 Add-on Therapies: หากไม่มีภาวะในข้อ 6.1 ให้พิจารณา:
  * เพิ่ม Hydrocortisone (หากสงสัย Relative Adrenal Insufficiency)
  * +/- Inotrope (เช่น Dobutamine) หากมีข้อบ่งชี้ (เช่น Cardiac dysfunction)
* 6.3 2nd Line Vasopressor: หากความดันยังตก ให้เพิ่มยาตัวที่สอง (2nd Vasopressor) คือ Adrenaline (Epinephrine)

***

### 📌 สรุปข้อห้าม/สิ่งที่ไม่แนะนำ (What NOT to do)

* ❌ ไม่ใช้ qSOFA เป็นเครื่องมือหลักในการคัดกรอง Sepsis อีกต่อไป
* ❌ หลีกเลี่ยงการใช้ Normal Saline (NSS) ในปริมาณมาก (ใช้ Balanced Crystalloid แทน)
* ❌ ไม่แนะนำให้ Empiric Antifungal เป็นประจำ ยกเว้นมีข้อบ่งชี้ทางคลินิกที่ชัดเจน

***

## Standing Order for Sepsis

<table data-header-hidden="false" data-header-sticky data-full-width="true"><thead><tr><th width="325" valign="top">Note</th><th width="493">Order for One Day</th><th>Order for Cotinuation</th></tr></thead><tbody><tr><td valign="top"><p>Case 45 yo female no UD BW50</p><p>ญาติบอกว่าคนไข้ปวดท้องลิ้นปี่มา 3 วัน ตาเหลืองตัวรุมมา 2 วัน วันนี้ปวดมากขึ้นเหนื่อยซึมไข้ไม่ลงเลยมารพ.<br></p><p>V/S BT 39.4 PR 110 BP 80/40 RR 20 SpO2 88%RA</p><p>PE: drowsiness, jaundice, crepitation BLL, marked tender RUQ, CRT 3sec, pitting edema 2+ BL, GCS11</p><p>Imp: Septic shock suspected from severe cholangitis +/- cholecystitis +/- acute pancreatitis</p></td><td><ul><li>On O2 cannula keep SpO2>94%</li><li>CBC, BUN, Cr, Elyte, Ca, Mg, P, LFT, PT, PTT, INR</li><li>Lactate = 6 mmol/L</li><li>H/C xII</li><li>ABG</li><li>POCT-glucose = 100mg%</li><li>CXR</li><li>LRS 500ml IV load in 30min</li><li>NE 8mg + D5W 250ml IV rate ___ml/hr (0.05mcg/kg/hr)</li><li>Serum lipase</li><li>EKG12leads</li></ul><p>(+/- TropT if STT change)</p><ul><li>Echo bedside</li><li>US IVC หลัง load คร</li><li>CTWA</li><li>Consult Sx if gangrenous cholecystitis for role of cholecystostomy</li></ul></td><td><ul><li>NPO</li><li>Record V/S, I/O</li><li>Retain Foley's catheter</li></ul><p><strong>Medication</strong></p><ul><li>Ceftriaxone 2 g IV OD</li><li>Metronidazole 500 mg IV q 8 hr</li><li>Paracetamol 500 mg RS q 4 hr prn fever/pain</li></ul></td></tr></tbody></table>
