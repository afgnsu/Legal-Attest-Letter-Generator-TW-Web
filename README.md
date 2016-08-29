# Legal Attest Letter Creator - Taiwan #
台灣郵局存證信函產生器 (PDF 格式)。A tool for creating a legal attest letter of Taiwan - in PDF format.

## Usage ##
```
tw-lal-creator -content content.txt -sentFrom name1 -sentFromAddr addr1 -sendTo name2 -sendToAddr addr2 -ccTo name2 -ccToAddr addr3 -setFontPath path
```

## Dependency ##
- [PyPDF2 1.26](https://github.com/mstamy2/PyPDF2)  
- [reportlab 3.3.0](https://bitbucket.org/rptlab/reportlab)
- [Letter format from Post Office of Taiwan](http://www.post.gov.tw/post/internet/Download/index.jsp?ID=220301)

## Roadmap ##
- Match PEP8  
- Provide application GUI
- Turn it into a cloud service (I'm considering)

## License ##
MIT