# hamonikr-usb-persistent

하모니카 OS ISO 이미지를 부팅 USB로 만들면 설치하지 않고 바로 사용할 수 있는 라이브 부팅을 제공합니다.

이 때 하모니카 팀에서 제공하는 live-usb-creator 프로그램을 이용해서 ISO를 제작시 %를 설정하면
USB의 공간 중 %로 지정한 공간을 부팅 USB 로 제작하고 남은 공간을 저장공간으로 생성할 수 있습니다.

이 패키지는 라이브 부팅 시 쓰기 가능한 공간이 있는 경우 해당 공간을 자동으로 바탕화면에 표시해주는 기능을 제공합니다.

# Install

 * 지원 OS : 하모니카 (>=3.0)

```
sudo apt update
sudo apt install hamonikr-usb-persistent
```

## 라이브 USB 부팅 후 데이터 저장 

라이브 USB로 부팅 후, 바탕화면에 보이는 mydata 폴더에 원하는 내용을 저장할 수 있습니다.
