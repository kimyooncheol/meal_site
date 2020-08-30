# 급식 정보 제공 사이트
## Project Info
- 나이스 교육정보 개방 포털에 있는 급식식단API를 이용하여 DB에 저장된 학교들의 급식을 알려주는 사이트 입니다.
## Picture
![index](https://github.com/kimyooncheol/meal_site/blob/master/image/index.PNG?raw=true)<br>
/index<br>
![food](https://github.com/kimyooncheol/meal_site/blob/master/image/meal.PNG?raw=true)<br>
/food<br>
## 구조도
![map](https://github.com/kimyooncheol/meal_site/blob/master/image/meal_map.PNG?raw=true)<br>
## DataBase구조
|sd_schul_code|schul_nm         |atpt_ofcdc_sc_code|atpt_ofcdc_sc_name|
|:-----------:|:---------------:|:----------------:|:----------------:|
|PRIMARY KEY VARCHAR(10) NOT NULL|VARCHAR(15) NOT NULL|VARCHAR(5) NOT NULL|VARCHAR(15) NOT NULL|
|'7800396'    |'원주의료고등학교' |'K10'            |'강원도교육청'      |
|'7821005'    |'단구중학교'      |'K10'             |'강원도교육청'     |
|'7811014'    |'계촌초등학교'    |'K10'             |'강원도교육청'     |
|'7800392'    |'문막고등학교'    |'K10'             |'강원도교육청'     |
|'7821037'    |'문막초등학교'    |'K10'             |'강원도교육청'     |

## Used Packages
```
- Flask: 백엔드를 구성하기 위해 사용되었습니다.
- requsets: Rest-API를 호출하기 위해 사용되었습니다.
- json: Rest-API에서 받아온 Json데이터를 파싱하기 위해 사용되었습니다.
- datetime: 당일 기준 급식을 받아오기 위해 사용되었습니다.
- flask-mysqldb : Flask를 Maria-DB와 연동하기 위해 사용되었습니다.
```
## Used Program
```
- Raspbian: 라즈베리파이 서버에서 리눅스 기반 개발을 위해 사용되었습니다.
- Maria-DB: DBMS로 사용되었습니다.
- BootStrap: 프론트엔드를 꾸미기 위해 사용되었습니다.
```
## Authors
- 김윤철
## License
This project is licensed under the MIT License
