# Print-Cost-counter
主要用于解决收费较低的打印店的打印计费问题。

传统打印店按张计费，通常要求覆盖率小于5%，但实际并无法检查真实的覆盖率，对于文档中图片较多的情况，由于一张仅收取0.15元，可能出现亏本的情况。
使用本项目即可实现按覆盖率计算打印费率，如一张纸收0.1元，文字覆盖率为5%，则一张收0.15元。
## 主要功能
根据文档实际使用墨水量，如纯黑计为1，纯白计为0，纯灰（透明度50%黑）计费0.5，计算文档打印费用。
