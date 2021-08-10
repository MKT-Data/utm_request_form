# UTM Source Naming Rules

<a href="https://raw.githubusercontent.com/MKT-Data/utm_request_form/master/UTM_Request_Form.xlsx" download>Download Request Form</a>

### Rule-1
The value must be in the English.

### Rule-2
If the utm_source already be used by other source, than use root domain(+top level domain) and lowercase the all letters as the value.

### Rule-3
If the source name is meaningful single word or acronym.

```
Use the source name as the utm_source directly, the first latter of the word and acronym should be capitalized.
```

| source name | utm_source  |
| ----------- | ----------- |
| Fabricacion | Fabricacion |
| IRJ         | IRJ         |

### Rule-4
If the source name is meaningful multiple words. 

```
Use "-" to connect each words, the first latter of each word and acronym should be capitalized.
```

| source name        | utm_source         |
| ------------------ | ------------------ |
| Electronics Weekly | Electronics-Weekly |
| Industry EMEA      | Industry-EMEA      |

### Rule-5
If the media name uses "&" to connect multiple charactars.

```
Use "and" to replace the "&", and capitalize the first latter of each word.
```

| source name | utm_source |
| ----------- | ---------- |
| A&D         | AandD      |

### Rule-6
If the media name is meaningful multiple words and uses "&".

Option 1 - 
```
Use "and" to replace the "&", and capitalize the first latter of each word.
```

Option 2 -
```
Use the root domain(+top level domain), and lowercase the all letters.
```

| source name           | utm_source             |
| --------------------- | ---------------------- |
| Computer & Automation | ComputerandAutomation  |
| Computer & Automation | computer-automation.de |

### Rule-7
If the media name is too complicated or too common or url or hard-to-read or there is no source name...

```
Use the root domain(+top level domain), and lowercase the all letters."
```

| source name                   | utm_source            |
| ----------------------------- | --------------------- |
| etz - Elektronik + Automation | ComputerandAutomation |
| www.evertiq.com               | evertiq.com           |
