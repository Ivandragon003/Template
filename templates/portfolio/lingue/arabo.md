# عرض تجاري

**رقم العرض:** {{string:offer_number}}  
**تاريخ العرض:** {{date:offer_date}}  
**صالح حتى:** {{date:offer_valid_until}}  
**اسم العميل:** {{string:client_name}}  
**الشركة المقدمة للعرض:** {{string:supplier_company}}

---

## 1. معلومات عامة

| الحقل | التفاصيل |
| --- | --- |
| اسم العميل | {{string:client_name}} |
| الجهة / الشركة | {{string:client_company}} |
| الرقم الضريبي | {{string:client_tax_number}} |
| الشخص المسؤول | {{string:client_contact_person}} |
| البريد الإلكتروني | {{email:client_email}} |
| رقم الهاتف | {{phone:client_phone}} |
| موضوع العرض | {{text:offer_subject}} |

---

## 2. ملخص تنفيذي

يهدف هذا العرض إلى تقديم خدمات تقنية ومهنية للعميل وفقًا للاحتياجات الموضحة أدناه، مع الالتزام بالجودة، المواعيد المتفق عليها، ومعايير التنفيذ المحددة.

| الحقل | التفاصيل |
| --- | --- |
| وصف مختصر للمشروع | {{text:project_summary}} |
| الهدف الرئيسي | {{text:project_objective}} |
| نطاق العمل | {{text:project_scope}} |
| طريقة التنفيذ | {{string:delivery_mode}} |
| مدة التنفيذ المتوقعة | {{integer:estimated_duration_days}} يوم |

---

## 3. الخدمات المقدمة

| رقم | الخدمة | الوصف | الوحدة | الكمية | السعر الفردي | الإجمالي |
| --- | --- | --- | --- | --- | --- | --- |
| S-01 | تحليل المتطلبات | دراسة المتطلبات وتحليل نطاق العمل | ساعة | {{integer:analysis_hours}} | {{currency:analysis_unit_price}} | {{currency:analysis_total}} |
| S-02 | تطوير الواجهة الخلفية | تطوير API والخدمات الخلفية | ساعة | {{integer:backend_hours}} | {{currency:backend_unit_price}} | {{currency:backend_total}} |
| S-03 | تطوير الواجهة الأمامية | تطوير واجهات المستخدم | ساعة | {{integer:frontend_hours}} | {{currency:frontend_unit_price}} | {{currency:frontend_total}} |
| S-04 | الاختبار وضمان الجودة | اختبارات وظيفية وتقنية | ساعة | {{integer:testing_hours}} | {{currency:testing_unit_price}} | {{currency:testing_total}} |
| S-05 | التوثيق الفني | إعداد الوثائق الفنية والتشغيلية | ساعة | {{integer:documentation_hours}} | {{currency:documentation_unit_price}} | {{currency:documentation_total}} |

---

## 4. الخدمات الاختيارية

| رقم | الخدمة الاختيارية | مشمولة | التكلفة |
| --- | --- | --- | --- |
| O-01 | الدعم الفني بعد التسليم | {{boolean:post_delivery_support_included}} | {{currency:post_delivery_support_cost}} |
| O-02 | تدريب المستخدمين | {{boolean:user_training_included}} | {{currency:user_training_cost}} |
| O-03 | الصيانة التطويرية | {{boolean:evolutionary_maintenance_included}} | {{currency:evolutionary_maintenance_cost}} |
| O-04 | النشر على بيئة الإنتاج | {{boolean:production_deployment_included}} | {{currency:production_deployment_cost}} |

---

## 5. الملخص المالي

| البند | القيمة |
| --- | --- |
| إجمالي الخدمات الأساسية | {{currency:subtotal_services}} |
| إجمالي الخدمات الاختيارية | {{currency:subtotal_optional_services}} |
| نسبة الخصم | {{percentage:discount_percentage}} |
| قيمة الخصم | {{currency:discount_amount}} |
| الإجمالي قبل الضريبة | {{currency:net_total}} |
| نسبة الضريبة | {{percentage:tax_percentage}} |
| قيمة الضريبة | {{currency:tax_amount}} |
| الإجمالي شامل الضريبة | {{currency:gross_total}} |

---

## 6. شروط الدفع

| الحقل | التفاصيل |
| --- | --- |
| الدفعة المقدمة | {{percentage:advance_payment_percentage}} |
| قيمة الدفعة المقدمة | {{currency:advance_payment_amount}} |
| الدفعة النهائية | {{currency:final_payment_amount}} |
| طريقة الدفع | {{string:payment_method}} |
| مدة السداد | {{integer:payment_terms_days}} يوم |
| ملاحظات الدفع | {{text:payment_notes}} |

---

## 7. الجدول الزمني للتنفيذ

| المرحلة | الوصف | المدة المتوقعة | تاريخ البداية | تاريخ النهاية |
| --- | --- | --- | --- | --- |
| المرحلة 1 | التحليل وتجهيز المتطلبات | {{integer:phase_1_duration_days}} يوم | {{date:phase_1_start_date}} | {{date:phase_1_end_date}} |
| المرحلة 2 | التطوير والتنفيذ | {{integer:phase_2_duration_days}} يوم | {{date:phase_2_start_date}} | {{date:phase_2_end_date}} |
| المرحلة 3 | الاختبار والمراجعة | {{integer:phase_3_duration_days}} يوم | {{date:phase_3_start_date}} | {{date:phase_3_end_date}} |
| المرحلة 4 | التسليم والنشر | {{integer:phase_4_duration_days}} يوم | {{date:phase_4_start_date}} | {{date:phase_4_end_date}} |

---

## 8. الافتراضات والقيود

| رقم | الافتراض / القيد | ينطبق |
| --- | --- | --- |
| A-01 | سيقوم العميل بتوفير المعلومات والوثائق المطلوبة في الوقت المناسب | {{boolean:client_documents_required}} |
| A-02 | سيتم تنفيذ العمل عن بُعد ما لم يتم الاتفاق على غير ذلك | {{boolean:remote_work_expected}} |
| A-03 | أي تغيير خارج نطاق العمل سيتم تسعيره بشكل منفصل | {{boolean:out_of_scope_billed_separately}} |
| A-04 | يتطلب النشر النهائي موافقة رسمية من العميل | {{boolean:client_approval_required}} |

---

## 9. شروط عامة

يلتزم الطرفان بالتعاون وتبادل المعلومات اللازمة لإنجاز المشروع ضمن المدة والجودة المتفق عليها. كما يلتزم مقدم الخدمة بالحفاظ على سرية المعلومات الفنية والتجارية التي يتم الاطلاع عليها أثناء تنفيذ العمل.

| الحقل | التفاصيل |
| --- | --- |
| مدة الالتزام بالسرية | {{integer:confidentiality_years}} سنوات |
| القانون المعمول به | {{string:governing_law}} |
| الجهة المختصة بالنزاع | {{string:competent_court}} |
| ملاحظات إضافية | {{text:additional_terms}} |

---

## 10. قبول العرض

يعتبر هذا العرض ساريًا حتى التاريخ المحدد أعلاه. بعد انتهاء مدة الصلاحية، قد تخضع الأسعار والشروط للمراجعة.

| الدور | الاسم | التاريخ | التوقيع |
| --- | --- | --- | --- |
| ممثل العميل | {{string:client_representative_name}} | {{date:client_signature_date}} | ____________ |
| ممثل مقدم الخدمة | {{string:supplier_representative_name}} | {{date:supplier_signature_date}} | ____________ |

---

_تم إعداد هذا العرض من قبل {{string:supplier_representative_name}} لصالح {{string:client_name}} — صالح حتى {{date:offer_valid_until}}._