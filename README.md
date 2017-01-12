# Java  
  
# CodeInterview  

1. SharedPoker.java - 4명에게 7장의 카드를 나누어주고 합이 가장 작은 사람 찾기(중복시 다시 나눠주기)   
 * NHN Technology Service  
   
2. NameList.java - 이유덕,이재영,권종표,이재영,박민호,강상희,이재영,김지완,최승혁,이성연,박영서,박민호,전경헌,송정환,김재성,이유덕,전경헌  
 1) 김씨와 이씨는 각각 몇 명?  
 2) "이재영"이라는 이름은 몇 번 반복되는가?  
 3) 중복을 제거한 이름을 출력  
 4) 중복을 제거한 이름을 오름차순으로 정렬하여 출력  
 * 사이냅소프트  
   
3. StockResult.java - 투자자의 순수익과 이득/손해 판단 출력  
 - 입력  
 1) 첫번째 줄에 투자액 a가 입력됨 (100 <= a <= 10,000)
 2) 두번째 줄에 투자일 수 b가 입력됨(1 <= b <= 10)  
 3) 세번째 줄에 일별 변동폭인 데이터가 날짜 갯수(b개)만큼 퍼센트 정수로 입력 (-100 ~ +100)  
 - 출력  
 1) 순수익(=총 수익(최종값) - 총 비용(투자금))을 소수점 첫째 자리에서 반올림하여 출력  
 2) 다음줄에 이득인 경우 "good", 본전일 경우 "same", 손해일 경우 "bad" 출력  
  * -0.5 < 순수익 < 0.5 인 경우 순수익은 0으로 간주  

4. 1부터 10,000까지 8이라는 숫자가 총 몇번 나오는가?
 1) 8이 포함되어 있는 숫자의 갯수를 카운팅 하는 것이 아니라 8이라는 숫자를 모두 카운팅 해야 한다.  
 ※ 예를들어 8808은 3, 8888은 4로 카운팅 해야 함  
  - 0000 ~ 9999로 => 4자리 숫자 10000개 = 40000개 => 0~9까지 10개가 같은 비율로 있으므로  
   => 40000 / 10 = 4000개  
  - 0 ~ 9999까지 XXX8(1000개), XX8X(1000개),X8XX(1000개),8XXX(1000개)  
   => 위의 두가지 방법 출처는 코딩도장  
   * 구글

5. Paris.java - 입력된 정수중 입력된 차만큼을 갖는 순서쌍 구하기  
 1) 정수의 개수와 차를 입력  
 2) 정수의 개수만큼 정수를 입력  
 3) 입력된 정수 중 입력된 차를 갖는 순서쌍 구하기  
  
6. BaryCenter.java - 배열의 중심 구하기  
 1) 배열을 입력 받은 후 좌측의 합과 우측의 합이 같은 중심이 있는지 찾기  
  
7. ZeroNine.java - 0과 9로만 이루어진 수 구하기  
 1) 정수를 입력 받은 후 해당 정수의 배수이면서 0과 9로만 이루어진 수 구하기  
  
8. StockInvest.java - 입력받은 날짜만큼 주가를 입력하고, 해당 주가중 최대금액 산출하기  
 1) 매일, 1주사거나, 일부 혹은 전부 팔거나, No Action 을 취할 수 있음  
  
9. MoreThanString.java - 입력된 String보다 큰 문자열 중 가장 작은 문자열 구하기  
  
# Study  
1. QuickSort  
2. LinkedList  