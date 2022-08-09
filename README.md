# try-catch
### try-catch문은 try문에서 사용된 코드들중에 오류가 있으면 catch문에서 찾아주는 함수입니다.
# 본문
![1](https://user-images.githubusercontent.com/104752580/183574025-8dae238a-da4a-457c-9f05-20a08a9407bc.PNG)
### 메인클래스에 5짜리 배열을 만든후 try문에 배열 3번째에 10값을 꽂아줍니다. try문에서 오류가 있으면 오류가 있습니다를 출력하는 catch문을 만들었습니다.
### try문에 오류가 없었기 때문에 정상적으로 돌아간 것을 볼 수 있습니다.
![2](https://user-images.githubusercontent.com/104752580/183574931-d816541a-4acb-4d29-8f79-c774bcb83af3.PNG)
### 이번에는 try문에 배열 7번째 1값을 넣어줬습니다. 제가 만든 배열은 5번째까지 있기 때문에 catch문에서 오류가 있습니다라고 출력된 것을 볼 수 있습니다.
![3](https://user-images.githubusercontent.com/104752580/183575309-0e74d68f-0f5a-44ee-a3d2-2bdec9a08383.PNG)
### catch문에 system.exit(0)이라는 함수를 넣었습니다. 이 함수는 프로그램을 종료시키는 함수입니다. 그렇기 때문에 프로그램이 시작되고 오류가 있습니다가 출력되고 프로그램이 종료 되었습니다가 나오기 전에 끝나는 것을 볼 수 있습니다.
![4](https://user-images.githubusercontent.com/104752580/183575739-a24b1289-f958-4b65-a2c9-e829da24203e.PNG)
### catch문에서 e는 오류를 검출해서 어디에 오류가 있는지 실제 오류를 검출하는 값입니다. 그렇기 때문에 e.pintStackTrace() 함수를 넣어주게 되면 실행창에 오류가 뜨는것을 볼 수 있습니다.
![5](https://user-images.githubusercontent.com/104752580/183576111-2e6c5b3b-c2e0-4b1d-afb6-1510e242cfbb.PNG)
### 실행창 맨 밑에 오류문 at tc.trycatch.main(trycatch.java:12)를 클릭하게 되면 어디서 오류가 났는지 찾아주는 것을 볼 수 있습니다.
