# 택배 배송 조회 for Whale

웨일 브라우저의 사이드바 확장 프로그램으로 간편하게 택배 배송을 조회할 수 있습니다.

### 택배 배송 조회 API

사이드바 내에서의 배송 조회는 'tracker.delivery([Github](https://github.com/shlee322/delivery-tracker))'의 코드를 기반으로 일부 수정하여 개인 서버를 통해 운영하고 있습니다.  
(현재 사용 중인 API 서버 코드 - ([Github](https://github.com/falsy/delivery-tracker)))

### 택배 배송 조회 참고 URI

새 창에서 이루어지는 배송 조회는 아래 URI을 통해 이루어집니다.

```
* 우체국 택배
https://service.epost.go.kr/trace.RetrieveDomRigiTraceList.comm?displayHeader=N&sid1=
* 우체국 국제우편 (EMS)
https://service.epost.go.kr/trace.RetrieveEmsRigiTraceList.comm?displayHeader=N&POST_CODE=
* CJ 대한통운
http://nplus.doortodoor.co.kr/web/detail.jsp?slipno=
* 한진 택배
http://www.hanjinexpress.hanjin.net/customer/hddcw18.tracking?w_num=
* 롯데 택배
https://www.lotteglogis.com/open/tracking?invno=
* 로젠 택배
https://www.ilogen.com/web/personal/trace/
* KGB 택배
http://www.kgbps.com/delivery/delivery_result.jsp?item_no=
* GS Postbox 택배
https://www.cvsnet.co.kr/invoice/tracking.do?invoice_no=
* CU 편의점 택배
https://www.cupost.co.kr/postbox/delivery/localResult.cupost?invoice_no=
* 경동 택배
http://kdexp.com/basicNewDelivery.kd?barcode=
* 일양로지스
http://www.ilyanglogis.com/functionality/card_form_waybill.asp?hawb_no=
```

### Screenshot

![Capture](/src/imgs/screenshot-1.png)
![Capture](/src/imgs/screenshot-2.png)
![Capture](/src/imgs/screenshot-3.png)

### Version

v1.7.5
