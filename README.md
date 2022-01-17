# DTmall
DT 개발팀 토이 프로젝트

# Git Script
```shell script
브랜치 생성 시: git checkout -b [날짜_기능명] (ex. 20210310_SearchProduct )
작업 내용 원격 브랜치에 반영 시: git push -u origin [브랜치명(생략가능)]
브랜치 직접 머징 시: git merge [머징 전략] [타겟 브랜치]
```
# Git Branch 정책
## Naming Rules 
- Feature 브랜치의 경우
> 날짜_기능_상세기능(Optional)
> - ex) 210309_board
> - ex) 210309_board_write

## 개발 가이드 
- 상수
> - 대문자 + SNAKE_CASE
- 변수
> - CamelCase
- 클래스
> - UpperCamel
- Method 
> - 동사 + 관련 job
- 주석
> - 날짜, 작업자, 역할
