
광주과학기술원 졸업 논문 (영문) 템플렛의 OVERLEAF 버전입니다.
저희 연구실 (EECS MLV)의 졸업자이신 유정민 선배님이 만들어둔 템플렛을 수정하여 OVERLEAF에 맞게 변형했습니다.

수정자: 윤광진 (전기전자컴퓨터공학부, 2019년 8월 졸업), yoon28@gist.ac.kr

주의: 영문 졸업 논문 작성에 맞도록 수정되었으며, 국문 졸업 논문 작성 환경에서는 테스트 하지 못했기때문에 작동 여부를 장담하지 못합니다.


메인 문서는 Dissertation.tex 입니다.
메인 문서의 [\code]를 수정하여 본인의 학위 및 소속 학과를 초록에 나타낼 수 있습니다.
예) \code{{MS/}{ME}} => 기계공학과 석사과정을 의미. MS 이후에 [/] 가 오는 이유는 학교 졸업 논문 템플릿이 학위과정과 소속학과를 [/]를 통해 구분하도록 되어있기 때문입니다.
    BS : 학사학위
    MS : 석사학위
    PhD: 박사학위

% 학과 코드, 현재 (2019년)
% IC - Information and Communications
% IM - Information and Mechatronics
% EC - Electric Engineering and Computer Science
% MS - Materials Science and Engineering
% ME - Mechatronics
% EN - Earth Science and Environmental Engineering
% LS - Life Science
% PH - Physics and Photon Science
% CH - Chemistry
% NA - Nanobio Materials and Electronics
% MD - Biomedical Science and Engineering
% ET - Integrated Technology 에너지 융합 학제
% CT - Integrated Technology 문화기술 융합 학제


논문 제목 설정하기 
[\etitle] 에 자신의 영어 논문 제목을 넣습니다.
[\ktitle] 에 자신의 한글 논문 제목을 넣습니다.

지도 교수 이름 설정하기
[\advisor] 에 지도교수의 영문 이름을 넣습니다.
[\kadvisor] 에 지도교수의 한글 이름을 넣습니다.

본인 이름 넣기
[\ename] 에 본인 영문 이름을 넣습니다.
[\kname] 에 본인 영문 이름을 넣습니다. 이때 한글자 씩 대괄호 [{}] 로 감싸서 넣습니다. 오른쪽 정렬로 넣으세요.

학번 설정하기
[\studentid] 에 본인 학번을 넣습니다.

기타 설정
[\coveryear] 졸업 년도 
[\advisorsigndate] 지도교수 사인 날짜
[\refereesigndate] 커미티 위원들 사인 날짜 (최종 사인 한 사람의 날짜)
[\refereeA] ~ [\refereeE] 커미티 위원들의 영문이름


폴더 구조
biblist.bib : bibtex, 논문에서 참조하는 레퍼런스들의 bibtex를 이곳에 위치시키세요.
Dissertation.tex : 메인 문서
gist.cls : 광주과기원 졸업 논문 템플렛의 클래스

chapters : 각 chapter들의 tex 파일이 위치하는 곳
	메인 문서에서 [\input] 커맨드로 포함 시킬 수 있습니다.

imgs: 논문에서 사용되는 이미지들이 위치하는 곳

misc: acknowledgements (감사의 글), appendix (첨부 문서), eabstract (영문 초록), kabstract (한글 초록), summary (요약문) 이 위치해 있는 곳
	메인 문서에서 [\input] 커맨드로 포함 시킬 수 있습니다.



