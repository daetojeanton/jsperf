---
title: test11 vs test22
setup: |
  
tests:
  -
    name: test11
    code: |
      var str = 'LAMY X LINE FRIENDS<br>BROWN in the RED 리미티드 에디션 드디어 출시! <img src="https://shop.line-scdn.net/sticon/v1/5/4/e/54ebda338d716822/desktop/100185_i.png" class="CMSticon" alt="􀂅"><br><br>강렬한 레드 틴케이스 속에서<br>숨 쉬고 있는 브라운 만년필을 만나보세요<br><br>완전히 진화된 실리콘 액세서리와 <br>한정판 잉크 카트리지 이벤트까지~<br>전작을 뛰어넘는 더욱 완벽해진 조합으로 <br>진정한 소장의 즐거움을 누려보세요!<br><br>- 온라인 스토어에서 구매하기<br>: <a href="http://lin.ee/9BiQ8dM" class="go_link" style="" target="_blank">http://lin.ee/9BiQ8dM</a><br><br>- 오프라인 스토어 판매처 확인하기<br>: <a href="http://lin.ee/8ZcqMbp" class="go_link" style="" target="_blank">http://lin.ee/8ZcqMbp</a><br><br><a limit="20" href="#라인프렌즈" title="#라인프렌즈" class="go_hashtag" rel="nofollow">#라인프렌즈</a> <a limit="20" href="#라미" title="#라미" class="go_hashtag" rel="nofollow">#라미</a> <a limit="20" href="#BROWNintheRED" title="#BROWNintheRED" class="go_hashtag" rel="nofollow">#BROWNintheRED</a> <a limit="20" href="#브라운잉크카트리지" title="#브라운잉크카트리지" class="go_hashtag" rel="nofollow">#브라운잉크카트리지</a> <a limit="20" href="#LAMY" title="#LAMY" class="go_hashtag" rel="nofollow">#LAMY</a> <a limit="20" href="#BROWN" title="#BROWN" class="go_hashtag" rel="nofollow">#BROWN</a> <a limit="20" href="#LINEFRIENDS" title="#LINEFRIENDS" class="go_hashtag" rel="nofollow">#LINEFRIENDS</a>';
      
      str = str.replace(/( )|<[^<>]*>/g, function(html, matched) {
          return (matched === " ") ? "&nbsp;" : html;
      });
  -
    name: test22
    code: |
      var str = 'LAMY X LINE FRIENDS<br>BROWN in the RED 리미티드 에디션 드디어 출시! <img src="https://shop.line-scdn.net/sticon/v1/5/4/e/54ebda338d716822/desktop/100185_i.png" class="CMSticon" alt="􀂅"><br><br>강렬한 레드 틴케이스 속에서<br>숨 쉬고 있는 브라운 만년필을 만나보세요<br><br>';
      
      str = str.replace(/( )|<[^<>]*>/g, function(html, matched) {
          return (matched === " ") ? "&nbsp;" : html;
      });
---
test
