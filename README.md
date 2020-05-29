# Melon Playlist Continuation

플레이리스트에 수록된 곡과 태그를 학습해 새롭게 주어진 플레이리스트의 곡과 태그를 예측

***
## 1. Data(1)

    song_meta.json: 곡 메타데이터
    train.json: 모델 학습용 파일
    genre_gn_all.json: 곡 메타데이터에 수록된 장르 정보
    val.json: 공개 리더보드용 문제파일
    test.json: 파이널 리더보드용 문제파일

***
## 2. Data(2)

    tag_song_pair.json: 태그:해당 태그와 연관된 song id
    tag_plylst_pair.json: 태그:해당 태그를 가지고 있는 playlist id
    tag_group_list.json/tag_group.json: 태그:해당 태그와 같은 playlist에 포함된 다른 태그들
    tag_similar_matrix50_1.json/tag_similar_matrix50_2.json: 태그간 유사도 정보
 
 ***
## 3. Code Files
  
    pair_tag_song.ipynb: tag_song_pair.json 파일을 얻기 위한 코드
    tag_cnt_over_ten_df.ipynb: 태그와 연관된 song id가 10 이상일 경우만 데이터에 포함
    tag_plylst_id.ipynb: tag_plylst_pair.json 파일을 얻기 위한 코드
    tag_group.ipynb: tag_group.json/tag_group_list.json 파일을 얻기 위한 코드
    tag_similar_arr/tag_similar_arr_1/tag_similar_arr_3.ipynb/matrix_distribute_multiplication.ipynb: tag_similar_matrix50_1/2.json을 얻기 위한 코드

***
## Team Members
- wyuinche
- movie5
- rlawjdghek
- Seunghoon
  
