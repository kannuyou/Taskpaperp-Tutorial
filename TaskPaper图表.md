| 逻辑符号       |   意义 | 比较符号 |          意义 |
| ---------- | ---: | ---- | ----------: |
| =          |   等于 | <    |          小于 |
| !=         |  不等于 | >    |          大于 |
|            |      | <=   |       小于或等于 |
|            |      | >=   |       大于或等于 |
|            |      |      |             |
| **字符**     |      |      |      **意义** |
| contains   |      |      |          包含 |
| beginswith |      |      |      以某字符开头 |
| endswith   |      |      |      以某字符结尾 |
| matches    |      |      | 包含（包括该行的标签） |

| 符号   |        意义 |
| ---- | --------: |
| i    | 忽略大小写（默认） |
| s    |    不忽略大小写 |
| n    |      比较数值 |
| d    |      比较日期 |

| 符号        |   意义 |
| --------- | ---: |
| union     |   并集 |
| intersect |   交集 |
| except    |   排除 |

| 重要，紧急       | @p intersect @due<=today+24h            |
| ----------- | --------------------------------------- |
| **重要，不紧急**  | **@p intersect @due>=today+24h**        |
| **不重要，紧急**  | **except @p intersect @due<=today+24h** |
| **不重要，不紧急** | **except @p intersect @due>=today+24h** |

  

| 绝对时间                 | 相对时间（当天）           |         |
| -------------------- | ------------------ | ------- |
| 2017                 | today              | 9:00    |
| 2017-10              | tomorrow           | 22:15   |
| 2017-10-01           | last/next Week     | 9am     |
| September            | last/next Month    | 9:00 am |
| September 15         | last/next Sun      | 9:00 pm |
|                      | last/next Sept     |         |
| **相对时间（当时）**         | last/next Sept 15  |         |
| 2 hours              | +2 days or -2 days |         |
| +2 hours or -2 hours | 2 days             |         |

| 语法                                     | 作用      |
| -------------------------------------- | ------- |
| @background-color: 颜色;                 | 编辑器背景颜色 |
| @text-color: 颜色;                       | 文字默认颜色  |
| item[data-type="project"] {color: 颜色;} | 项目颜色    |
| run[tag="data-标签名"] {color: 颜色;}       | 标签颜色    |

