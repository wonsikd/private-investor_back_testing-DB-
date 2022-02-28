# private-investor_back_testing-DB-

본 프로젝트는 DB 금융 공모전을 위해 제작된 파일입니다.

# 파일설명
 main_file : DB_stock_bactesting_final
 실제 백테스팅 및 시각화를 한 코드입니다. 전략이 총 3개로 나뉘어져 있어 유의사항을 차모하여 파일을 실행하시길 바랍니다.
 
 sub_file : naver_stock_crawling
 네이버 종목토론 게시글을 크롤링해오는 코드입니다. / 데이터를 가져오는데 시간이 오래걸리므로 필요시
 dnstlrdl1@naver.com 으로 메일 부탁드립니다.
 
 sub_file : marcov_hidden_stat_model
 히든 마르코프 모델을 이용하여 국면을 측정한 코드입니다.
 
 
 data_file : k_df_score.xlsx
 main_file을 이용해서 날짜마다 스코어링한 값입니다. 시간을 단축하기 위해서 한번 구한뒤 파일을 저장하였습니 다.
 data_file : korea_price.xlsx
 블룸버그 터미널을 이용하여 주식종목들의 날짜별 가격을 구한 데이터 엑셀파일입니다. 휴장일경우 전날의 가격을 채워넣게끔 설정해주었습니다.
 
 data_file : kospi_universe.xlsx
 KRX데이터를 이용하여 코스피200이 편입 혹은 편출 시 그 데이터를 반영해주었습니다, 시기별 kospi200의 universe가 데이터프레임화 되어있습니다.
 
 data_file : 4regimes.csv
 sub_file을 이용하여 국면을 예측한 값이 미리 저장되어 있는 코드입니다. 이 파일이 있어야지 mainfile이 백테스팅이 가능합니다. 
 
 data_file : 코스피 자금.csv
 KRX에서 가져온 코스피 개인 거래대금 데이터입니다.

자세한내용은 첨부된 논문을 참고하시면 될거 같습니다.
감사합니다.
