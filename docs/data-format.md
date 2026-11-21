# 记录格式

情境判断记录以 id、scenario、standard、tool_advice、student_reason、teacher_review 保存情境、标准版本、建议、学生理由及教师复核。

记录以 UTF-8 JSON 保存，顶层包含 dataset 和 records。每条记录的 id 在文件中唯一。`fixtures/records.json` 中的例子用于说明输入字段和状态取值。
