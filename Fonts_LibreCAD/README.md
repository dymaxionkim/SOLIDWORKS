# LibreCAD

* 리눅스 버전에는 유니코드 CJK 문자가 포함된 wqy-unicode.lff 폰트가 없다.
* 이유는, 리눅스 버전은 github에서 호스팅하기 때문에 용량한계 때문에 그런 것 같다.
* 따라서 해당 폰트는 별도로 다운로드 받아서 다음 명령으로 위치시켜주는 것이 좋겠다.

```
sudo mv /usr/share/librecad/fonts/standard.lff /usr/share/librecad/fonts/standard.lff.old
sudo cp wqy-unicode.lff /usr/share/librecad/fonts/wqy-unicode.lff
sudo cp wqy-unicode.lff /usr/share/librecad/fonts/standard.lff
```
