 "public": false,
  "files": {
    "index.html": {
      "content": "<!DOCTYPE\ html>\n<html\ lang="zh-CN">\n<head>\n\ \ <meta\ charset="UTF-8">\n\ \ <meta\ name="viewport"\ content="width=device-width,\ initial-scale=1\.0">\n\ \ <title>3DM娓告垙缃\?-\ 鍏ㄧ悆鐑棬娓告垙鏀荤暐涓庤祫璁\?/title>\n\ \ <style>\n\ \ \ \ \*\ \{\n\ \ \ \ \ \ margin:\ 0;\n\ \ \ \ \ \ padding:\ 0;\n\ \ \ \ \ \ box-sizing:\ border-box;\n\ \ \ \ }\n\n\ \ \ \ body\ \{\n\ \ \ \ \ \ font-family:\ 'Microsoft\ YaHei',\ 'PingFang\ SC',\ sans-serif;\n\ \ \ \ \ \ background:\ \#121212;\n\ \ \ \ \ \ color:\ \#e0e0e0;\n\ \ \ \ \ \ line-height:\ 1\.6;\n\ \ \ \ }\n\n\ \ \ \ a\ \{\n\ \ \ \ \ \ text-decoration:\ none;\n\ \ \ \ \ \ color:\ inherit;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Header\ \*/\n\ \ \ \ header\ \{\n\ \ \ \ \ \ background:\ linear-gradient\(90deg,\ \#e74c3c,\ \#c0392b\);\n\ \ \ \ \ \ padding:\ 10px\ 40px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ space-between;\n\ \ \ \ \ \ position:\ sticky;\n\ \ \ \ \ \ top:\ 0;\n\ \ \ \ \ \ z-index:\ 1000;\n\ \ \ \ }\n\n\ \ \ \ \.logo\ \{\n\ \ \ \ \ \ font-size:\ 1\.8em;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ text-shadow:\ 2px\ 2px\ 4px\ rgba\(0,0,0,0\.3\);\n\ \ \ \ }\n\n\ \ \ \ \.logo\ span\ \{\n\ \ \ \ \ \ color:\ \#f39c12;\n\ \ \ \ }\n\n\ \ \ \ \.header-nav\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ gap:\ 25px;\n\ \ \ \ }\n\n\ \ \ \ \.header-nav\ a\ \{\n\ \ \ \ \ \ color:\ rgba\(255,255,255,0\.9\);\n\ \ \ \ \ \ text-decoration:\ none;\n\ \ \ \ \ \ font-size:\ 0\.95em;\n\ \ \ \ \ \ transition:\ color\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.header-nav\ a:hover\ \{\n\ \ \ \ \ \ color:\ \#f39c12;\n\ \ \ \ }\n\n\ \ \ \ \.search-box\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ gap:\ 8px;\n\ \ \ \ }\n\n\ \ \ \ \.search-box\ input\ \{\n\ \ \ \ \ \ padding:\ 8px\ 15px;\n\ \ \ \ \ \ border:\ none;\n\ \ \ \ \ \ border-radius:\ 4px;\n\ \ \ \ \ \ background:\ rgba\(255,255,255,0\.95\);\n\ \ \ \ \ \ color:\ \#333;\n\ \ \ \ \ \ width:\ 200px;\n\ \ \ \ }\n\n\ \ \ \ \.search-box\ button\ \{\n\ \ \ \ \ \ padding:\ 8px\ 20px;\n\ \ \ \ \ \ background:\ \#2c3e50;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ border:\ none;\n\ \ \ \ \ \ border-radius:\ 4px;\n\ \ \ \ \ \ cursor:\ pointer;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Banner\ \*/\n\ \ \ \ \.banner\ \{\n\ \ \ \ \ \ background:\ linear-gradient\(135deg,\ \#1a1a2e\ 0%,\ \#16213e\ 100%\);\n\ \ \ \ \ \ padding:\ 100px\ 40px;\n\ \ \ \ \ \ text-align:\ center;\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ }\n\n\ \ \ \ \.banner::before\ \{\n\ \ \ \ \ \ content:\ '';\n\ \ \ \ \ \ position:\ absolute;\n\ \ \ \ \ \ top:\ 0;\n\ \ \ \ \ \ left:\ 0;\n\ \ \ \ \ \ right:\ 0;\n\ \ \ \ \ \ bottom:\ 0;\n\ \ \ \ \ \ background:\ radial-gradient\(circle\ at\ 30%\ 50%,\ rgba\(231,\ 76,\ 60,\ 0\.15\)\ 0%,\ transparent\ 50%\),\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ radial-gradient\(circle\ at\ 70%\ 50%,\ rgba\(243,\ 156,\ 18,\ 0\.1\)\ 0%,\ transparent\ 50%\);\n\ \ \ \ }\n\n\ \ \ \ \.banner\ h1\ \{\n\ \ \ \ \ \ font-size:\ 3\.2em;\n\ \ \ \ \ \ margin-bottom:\ 15px;\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ }\n\n\ \ \ \ \.banner\ h1\ span\ \{\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.banner\ p\ \{\n\ \ \ \ \ \ font-size:\ 1\.15em;\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ }\n\n\ \ \ \ \.banner-tags\ \{\n\ \ \ \ \ \ margin-top:\ 25px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ gap:\ 15px;\n\ \ \ \ \ \ flex-wrap:\ wrap;\n\ \ \ \ }\n\n\ \ \ \ \.banner-tag\ \{\n\ \ \ \ \ \ padding:\ 6px\ 18px;\n\ \ \ \ \ \ border-radius:\ 20px;\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ background:\ rgba\(255,255,255,0\.1\);\n\ \ \ \ \ \ border:\ 1px\ solid\ rgba\(255,255,255,0\.2\);\n\ \ \ \ \ \ cursor:\ pointer;\n\ \ \ \ \ \ transition:\ all\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.banner-tag:hover\ \{\n\ \ \ \ \ \ background:\ \#e74c3c;\n\ \ \ \ \ \ border-color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Container\ \*/\n\ \ \ \ \.container\ \{\n\ \ \ \ \ \ max-width:\ 1400px;\n\ \ \ \ \ \ margin:\ 0\ auto;\n\ \ \ \ \ \ padding:\ 40px;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Section\ Title\ \*/\n\ \ \ \ \.section-title\ \{\n\ \ \ \ \ \ font-size:\ 1\.5em;\n\ \ \ \ \ \ padding-bottom:\ 15px;\n\ \ \ \ \ \ border-bottom:\ 3px\ solid\ \#e74c3c;\n\ \ \ \ \ \ margin-bottom:\ 30px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 10px;\n\ \ \ \ }\n\n\ \ \ \ \.section-title\ \.hot\ \{\n\ \ \ \ \ \ background:\ \#e74c3c;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ font-size:\ 0\.5em;\n\ \ \ \ \ \ padding:\ 3px\ 8px;\n\ \ \ \ \ \ border-radius:\ 3px;\n\ \ \ \ }\n\n\ \ \ \ \.section-title\ \.new\ \{\n\ \ \ \ \ \ background:\ \#2ecc71;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ font-size:\ 0\.5em;\n\ \ \ \ \ \ padding:\ 3px\ 8px;\n\ \ \ \ \ \ border-radius:\ 3px;\n\ \ \ \ }\n\n\ \ \ \ \.section-title\ \.more\ \{\n\ \ \ \ \ \ margin-left:\ auto;\n\ \ \ \ \ \ font-size:\ 0\.6em;\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ font-weight:\ normal;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Game\ Grid\ \*/\n\ \ \ \ \.game-grid\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ repeat\(auto-fill,\ minmax\(280px,\ 1fr\)\);\n\ \ \ \ \ \ gap:\ 25px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.game-card\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 10px;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ \ \ transition:\ transform\ 0\.3s,\ box-shadow\ 0\.3s;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.game-card:hover\ \{\n\ \ \ \ \ \ transform:\ translateY\(-5px\);\n\ \ \ \ \ \ box-shadow:\ 0\ 15px\ 30px\ rgba\(0,0,0,0\.5\);\n\ \ \ \ \ \ border-color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.game-cover\ \{\n\ \ \ \ \ \ height:\ 180px;\n\ \ \ \ \ \ background:\ \#2c3e50;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ font-size:\ 4em;\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ }\n\n\ \ \ \ \.game-cover\ img\ \{\n\ \ \ \ \ \ width:\ 100%;\n\ \ \ \ \ \ height:\ 100%;\n\ \ \ \ \ \ object-fit:\ cover;\n\ \ \ \ }\n\n\ \ \ \ \.game-cover\ \.emoji\ \{\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ \ \ z-index:\ 1;\n\ \ \ \ }\n\n\ \ \ \ \.game-cover\ \.score\ \{\n\ \ \ \ \ \ position:\ absolute;\n\ \ \ \ \ \ top:\ 10px;\n\ \ \ \ \ \ right:\ 10px;\n\ \ \ \ \ \ background:\ rgba\(231,\ 76,\ 60,\ 0\.9\);\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ padding:\ 3px\ 10px;\n\ \ \ \ \ \ border-radius:\ 4px;\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ z-index:\ 2;\n\ \ \ \ }\n\n\ \ \ \ \.game-info\ \{\n\ \ \ \ \ \ padding:\ 20px;\n\ \ \ \ }\n\n\ \ \ \ \.game-title\ \{\n\ \ \ \ \ \ font-size:\ 1\.2em;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ margin-bottom:\ 8px;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ }\n\n\ \ \ \ \.game-tag\ \{\n\ \ \ \ \ \ display:\ inline-block;\n\ \ \ \ \ \ padding:\ 3px\ 10px;\n\ \ \ \ \ \ border-radius:\ 4px;\n\ \ \ \ \ \ font-size:\ 0\.75em;\n\ \ \ \ \ \ margin-bottom:\ 10px;\n\ \ \ \ }\n\n\ \ \ \ \.tag-action\ \{\ background:\ rgba\(231,\ 76,\ 60,\ 0\.2\);\ color:\ \#e74c3c;\ }\n\ \ \ \ \.tag-rpg\ \{\ background:\ rgba\(155,\ 89,\ 182,\ 0\.2\);\ color:\ \#9b59b6;\ }\n\ \ \ \ \.tag-adventure\ \{\ background:\ rgba\(52,\ 152,\ 219,\ 0\.2\);\ color:\ \#3498db;\ }\n\ \ \ \ \.tag-strategy\ \{\ background:\ rgba\(46,\ 204,\ 113,\ 0\.2\);\ color:\ \#2ecc71;\ }\n\ \ \ \ \.tag-shooter\ \{\ background:\ rgba\(241,\ 196,\ 15,\ 0\.2\);\ color:\ \#f1c40f;\ }\n\ \ \ \ \.tag-horror\ \{\ background:\ rgba\(192,\ 57,\ 43,\ 0\.2\);\ color:\ \#c0392b;\ }\n\n\ \ \ \ \.game-desc\ \{\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ line-height:\ 1\.6;\n\ \ \ \ \ \ margin-bottom:\ 12px;\n\ \ \ \ }\n\n\ \ \ \ \.game-meta\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ justify-content:\ space-between;\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ }\n\n\ \ \ \ /\*\ News\ List\ \*/\n\ \ \ \ \.news-list\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ flex-direction:\ column;\n\ \ \ \ \ \ gap:\ 20px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.news-item\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 10px;\n\ \ \ \ \ \ padding:\ 25px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ gap:\ 20px;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ \ \ transition:\ border-color\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.news-item:hover\ \{\n\ \ \ \ \ \ border-color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.news-thumb\ \{\n\ \ \ \ \ \ width:\ 200px;\n\ \ \ \ \ \ height:\ 130px;\n\ \ \ \ \ \ background:\ \#2c3e50;\n\ \ \ \ \ \ border-radius:\ 8px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ font-size:\ 2\.5em;\n\ \ \ \ \ \ flex-shrink:\ 0;\n\ \ \ \ \ \ position:\ relative;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ }\n\n\ \ \ \ \.news-thumb\ img\ \{\n\ \ \ \ \ \ width:\ 100%;\n\ \ \ \ \ \ height:\ 100%;\n\ \ \ \ \ \ object-fit:\ cover;\n\ \ \ \ }\n\n\ \ \ \ \.news-thumb\ \.type-tag\ \{\n\ \ \ \ \ \ position:\ absolute;\n\ \ \ \ \ \ top:\ 8px;\n\ \ \ \ \ \ left:\ 8px;\n\ \ \ \ \ \ padding:\ 2px\ 8px;\n\ \ \ \ \ \ border-radius:\ 3px;\n\ \ \ \ \ \ font-size:\ 0\.7em;\n\ \ \ \ \ \ background:\ rgba\(231,\ 76,\ 60,\ 0\.9\);\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ }\n\n\ \ \ \ \.news-content\ \{\n\ \ \ \ \ \ flex:\ 1;\n\ \ \ \ }\n\n\ \ \ \ \.news-title\ \{\n\ \ \ \ \ \ font-size:\ 1\.15em;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ margin-bottom:\ 10px;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ }\n\n\ \ \ \ \.news-title\ a:hover\ \{\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.news-desc\ \{\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ margin-bottom:\ 12px;\n\ \ \ \ \ \ line-height:\ 1\.7;\n\ \ \ \ }\n\n\ \ \ \ \.news-meta\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ gap:\ 20px;\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ }\n\n\ \ \ \ \.news-meta\ span\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 5px;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Strategy\ Section\ \*/\n\ \ \ \ \.strategy-section\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ 2fr\ 1fr;\n\ \ \ \ \ \ gap:\ 30px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-main\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 12px;\n\ \ \ \ \ \ padding:\ 25px;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-item\ \{\n\ \ \ \ \ \ padding:\ 20px\ 0;\n\ \ \ \ \ \ border-bottom:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-item:last-child\ \{\n\ \ \ \ \ \ border-bottom:\ none;\n\ \ \ \ \ \ padding-bottom:\ 0;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-item\ h4\ \{\n\ \ \ \ \ \ font-size:\ 1\.1em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 8px;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-item\ p\ \{\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ line-height:\ 1\.7;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-item\ \.step\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 10px;\n\ \ \ \ \ \ margin-top:\ 10px;\n\ \ \ \ }\n\n\ \ \ \ \.step-num\ \{\n\ \ \ \ \ \ width:\ 24px;\n\ \ \ \ \ \ height:\ 24px;\n\ \ \ \ \ \ background:\ \#e74c3c;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ border-radius:\ 50%;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ font-size:\ 0\.8em;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-sidebar\ \.side-card\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 12px;\n\ \ \ \ \ \ padding:\ 20px;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ \ \ margin-bottom:\ 20px;\n\ \ \ \ }\n\n\ \ \ \ \.strategy-sidebar\ h4\ \{\n\ \ \ \ \ \ font-size:\ 1em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 15px;\n\ \ \ \ \ \ padding-bottom:\ 10px;\n\ \ \ \ \ \ border-bottom:\ 2px\ solid\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.side-item\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ gap:\ 12px;\n\ \ \ \ \ \ padding:\ 12px\ 0;\n\ \ \ \ \ \ border-bottom:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.side-item:last-child\ \{\n\ \ \ \ \ \ border-bottom:\ none;\n\ \ \ \ }\n\n\ \ \ \ \.side-num\ \{\n\ \ \ \ \ \ font-size:\ 1\.5em;\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ width:\ 30px;\n\ \ \ \ }\n\n\ \ \ \ \.side-content\ h5\ \{\n\ \ \ \ \ \ font-size:\ 0\.95em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 4px;\n\ \ \ \ }\n\n\ \ \ \ \.side-content\ p\ \{\n\ \ \ \ \ \ font-size:\ 0\.8em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Tools\ Section\ \*/\n\ \ \ \ \.tools-grid\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ repeat\(auto-fill,\ minmax\(300px,\ 1fr\)\);\n\ \ \ \ \ \ gap:\ 20px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.tool-card\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 10px;\n\ \ \ \ \ \ padding:\ 20px;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 15px;\n\ \ \ \ \ \ transition:\ all\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.tool-card:hover\ \{\n\ \ \ \ \ \ border-color:\ \#e74c3c;\n\ \ \ \ \ \ background:\ \#252525;\n\ \ \ \ }\n\n\ \ \ \ \.tool-icon\ \{\n\ \ \ \ \ \ width:\ 50px;\n\ \ \ \ \ \ height:\ 50px;\n\ \ \ \ \ \ background:\ linear-gradient\(135deg,\ \#e74c3c,\ \#c0392b\);\n\ \ \ \ \ \ border-radius:\ 10px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ font-size:\ 1\.5em;\n\ \ \ \ }\n\n\ \ \ \ \.tool-info\ \{\n\ \ \ \ \ \ flex:\ 1;\n\ \ \ \ }\n\n\ \ \ \ \.tool-info\ h4\ \{\n\ \ \ \ \ \ font-size:\ 1em;\n\ \ \ \ \ \ margin-bottom:\ 5px;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ }\n\n\ \ \ \ \.tool-info\ p\ \{\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ }\n\n\ \ \ \ \.tool-download\ \{\n\ \ \ \ \ \ padding:\ 8px\ 15px;\n\ \ \ \ \ \ background:\ \#e74c3c;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ border:\ none;\n\ \ \ \ \ \ border-radius:\ 6px;\n\ \ \ \ \ \ cursor:\ pointer;\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ transition:\ background\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.tool-download:hover\ \{\n\ \ \ \ \ \ background:\ \#c0392b;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Ranking\ Section\ \*/\n\ \ \ \ \.ranking-section\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ repeat\(3,\ 1fr\);\n\ \ \ \ \ \ gap:\ 25px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.ranking-card\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 12px;\n\ \ \ \ \ \ padding:\ 25px;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.ranking-card\ h4\ \{\n\ \ \ \ \ \ font-size:\ 1\.1em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 20px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 8px;\n\ \ \ \ }\n\n\ \ \ \ \.ranking-list\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ flex-direction:\ column;\n\ \ \ \ \ \ gap:\ 15px;\n\ \ \ \ }\n\n\ \ \ \ \.ranking-item\ \{\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ gap:\ 12px;\n\ \ \ \ \ \ padding:\ 10px;\n\ \ \ \ \ \ border-radius:\ 8px;\n\ \ \ \ \ \ transition:\ background\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.ranking-item:hover\ \{\n\ \ \ \ \ \ background:\ \#252525;\n\ \ \ \ }\n\n\ \ \ \ \.rank-num\ \{\n\ \ \ \ \ \ width:\ 28px;\n\ \ \ \ \ \ height:\ 28px;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ border-radius:\ 6px;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ }\n\n\ \ \ \ \.rank-1\ \{\ background:\ linear-gradient\(135deg,\ \#f39c12,\ \#e67e22\);\ color:\ \#fff;\ }\n\ \ \ \ \.rank-2\ \{\ background:\ linear-gradient\(135deg,\ \#95a5a6,\ \#7f8c8d\);\ color:\ \#fff;\ }\n\ \ \ \ \.rank-3\ \{\ background:\ linear-gradient\(135deg,\ \#cd6133,\ \#a04000\);\ color:\ \#fff;\ }\n\ \ \ \ \.rank-other\ \{\ background:\ \#333;\ color:\ \#888;\ }\n\n\ \ \ \ \.rank-info\ \{\n\ \ \ \ \ \ flex:\ 1;\n\ \ \ \ }\n\n\ \ \ \ \.rank-info\ h5\ \{\n\ \ \ \ \ \ font-size:\ 0\.95em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 2px;\n\ \ \ \ }\n\n\ \ \ \ \.rank-info\ p\ \{\n\ \ \ \ \ \ font-size:\ 0\.8em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ }\n\n\ \ \ \ \.rank-value\ \{\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Hardware\ Section\ \*/\n\ \ \ \ \.hardware-grid\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ repeat\(auto-fill,\ minmax\(300px,\ 1fr\)\);\n\ \ \ \ \ \ gap:\ 25px;\n\ \ \ \ \ \ margin-bottom:\ 60px;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-card\ \{\n\ \ \ \ \ \ background:\ \#1e1e1e;\n\ \ \ \ \ \ border-radius:\ 12px;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ \ \ border:\ 1px\ solid\ \#333;\n\ \ \ \ \ \ transition:\ all\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-card:hover\ \{\n\ \ \ \ \ \ border-color:\ \#e74c3c;\n\ \ \ \ \ \ transform:\ translateY\(-3px\);\n\ \ \ \ }\n\n\ \ \ \ \.hardware-img\ \{\n\ \ \ \ \ \ height:\ 160px;\n\ \ \ \ \ \ background:\ \#2c3e50;\n\ \ \ \ \ \ display:\ flex;\n\ \ \ \ \ \ align-items:\ center;\n\ \ \ \ \ \ justify-content:\ center;\n\ \ \ \ \ \ font-size:\ 3em;\n\ \ \ \ \ \ overflow:\ hidden;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-img\ img\ \{\n\ \ \ \ \ \ width:\ 100%;\n\ \ \ \ \ \ height:\ 100%;\n\ \ \ \ \ \ object-fit:\ cover;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-info\ \{\n\ \ \ \ \ \ padding:\ 20px;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-info\ h4\ \{\n\ \ \ \ \ \ font-size:\ 1\.1em;\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 8px;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-info\ p\ \{\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ \ \ margin-bottom:\ 12px;\n\ \ \ \ \ \ line-height:\ 1\.6;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-price\ \{\n\ \ \ \ \ \ font-size:\ 1\.3em;\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ \ \ font-weight:\ bold;\n\ \ \ \ }\n\n\ \ \ \ \.hardware-price\ del\ \{\n\ \ \ \ \ \ font-size:\ 0\.7em;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ \ \ margin-left:\ 8px;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Footer\ \*/\n\ \ \ \ footer\ \{\n\ \ \ \ \ \ background:\ \#0a0a0a;\n\ \ \ \ \ \ padding:\ 50px\ 40px;\n\ \ \ \ \ \ border-top:\ 1px\ solid\ \#333;\n\ \ \ \ }\n\n\ \ \ \ \.footer-main\ \{\n\ \ \ \ \ \ display:\ grid;\n\ \ \ \ \ \ grid-template-columns:\ 2fr\ 1fr\ 1fr\ 1fr;\n\ \ \ \ \ \ gap:\ 40px;\n\ \ \ \ \ \ max-width:\ 1400px;\n\ \ \ \ \ \ margin:\ 0\ auto\ 30px;\n\ \ \ \ }\n\n\ \ \ \ \.footer-about\ \.logo\ \{\n\ \ \ \ \ \ margin-bottom:\ 15px;\n\ \ \ \ }\n\n\ \ \ \ \.footer-about\ p\ \{\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ line-height:\ 1\.8;\n\ \ \ \ }\n\n\ \ \ \ \.footer-col\ h4\ \{\n\ \ \ \ \ \ color:\ \#fff;\n\ \ \ \ \ \ margin-bottom:\ 20px;\n\ \ \ \ \ \ font-size:\ 1em;\n\ \ \ \ }\n\n\ \ \ \ \.footer-col\ a\ \{\n\ \ \ \ \ \ display:\ block;\n\ \ \ \ \ \ color:\ \#666;\n\ \ \ \ \ \ font-size:\ 0\.9em;\n\ \ \ \ \ \ margin-bottom:\ 12px;\n\ \ \ \ \ \ transition:\ color\ 0\.3s;\n\ \ \ \ }\n\n\ \ \ \ \.footer-col\ a:hover\ \{\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ \.footer-bottom\ \{\n\ \ \ \ \ \ text-align:\ center;\n\ \ \ \ \ \ padding-top:\ 30px;\n\ \ \ \ \ \ border-top:\ 1px\ solid\ \#222;\n\ \ \ \ \ \ max-width:\ 1400px;\n\ \ \ \ \ \ margin:\ 0\ auto;\n\ \ \ \ }\n\n\ \ \ \ \.footer-bottom\ p\ \{\n\ \ \ \ \ \ color:\ \#555;\n\ \ \ \ \ \ font-size:\ 0\.85em;\n\ \ \ \ }\n\n\ \ \ \ \.footer-bottom\ a\ \{\n\ \ \ \ \ \ color:\ \#888;\n\ \ \ \ }\n\n\ \ \ \ \.footer-bottom\ a:hover\ \{\n\ \ \ \ \ \ color:\ \#e74c3c;\n\ \ \ \ }\n\n\ \ \ \ /\*\ Responsive\ \*/\n\ \ \ \ @media\ \(max-width:\ 1024px\)\ \{\n\ \ \ \ \ \ \.strategy-section\ \{\n\ \ \ \ \ \ \ \ grid-template-columns:\ 1fr;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.ranking-section\ \{\n\ \ \ \ \ \ \ \ grid-template-columns:\ 1fr;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.footer-main\ \{\n\ \ \ \ \ \ \ \ grid-template-columns:\ 1fr\ 1fr;\n\ \ \ \ \ \ }\n\ \ \ \ }\n\n\ \ \ \ @media\ \(max-width:\ 768px\)\ \{\n\ \ \ \ \ \ \.header-nav,\ \.search-box\ \{\n\ \ \ \ \ \ \ \ display:\ none;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.banner\ h1\ \{\n\ \ \ \ \ \ \ \ font-size:\ 2em;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.news-item\ \{\n\ \ \ \ \ \ \ \ flex-direction:\ column;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.news-thumb\ \{\n\ \ \ \ \ \ \ \ width:\ 100%;\n\ \ \ \ \ \ \ \ height:\ 150px;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ header\ \{\n\ \ \ \ \ \ \ \ padding:\ 15px\ 20px;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.container\ \{\n\ \ \ \ \ \ \ \ padding:\ 20px;\n\ \ \ \ \ \ }\n\n\ \ \ \ \ \ \.footer-main\ \{\n\ \ \ \ \ \ \ \ grid-template-columns:\ 1fr;\n\ \ \ \ \ \ }\n\ \ \ \ }\n\ \ </style>\n</head>\n<body>\n\ \ <header>\n\ \ \ \ <div\ class="logo">3DM<span>娓告垙缃\?/span></div>\n\ \ \ \ <nav\ class="header-nav">\n\ \ \ \ \ \ <a\ href="\#">棣栭〉</a>\n\ \ \ \ \ \ <a\ href="\#news">娓告垙璧勮</a>\n\ \ \ \ \ \ <a\ href="\#strategy">鏀荤暐涓績</a>\n\ \ \ \ \ \ <a\ href="\#tools">娓告垙宸ュ叿</a>\n\ \ \ \ \ \ <a\ href="\#ranking">鎺掕姒\?/a>\n\ \ \ \ \ \ <a\ href="\#hardware">纭欢璇勬祴</a>\n\ \ \ \ </nav>\n\ \ \ \ <div\ class="search-box">\n\ \ \ \ \ \ <input\ type="text"\ placeholder="鎼滅储娓告垙銆佹敾鐣\?\.\.">\n\ \ \ \ \ \ <button>鎼滅储</button>\n\ \ \ \ </div>\n\ \ </header>\n\n\ \ <section\ class="banner"\ id="home">\n\ \ \ \ <h1>鍏ㄧ悆鐑棬<span>娓告垙</span>涓€缃戞墦灏\?/h1>\n\ \ \ \ <p>绗竴鏃堕棿鑾峰彇娓告垙璧勮銆佷笓涓氭敾鐣ャ€佸疄鐢ㄥ伐鍏凤紝涓庡叏鐞冪帺瀹朵竴璧风晠鐜\?/p>\n\ \ \ \ <div\ class="banner-tags">\n\ \ \ \ \ \ <span\ class="banner-tag">馃幃\ 鍔ㄤ綔鍐掗櫓</span>\n\ \ \ \ \ \ <span\ class="banner-tag">鈿旓笍\ 瑙掕壊鎵紨</span>\n\ \ \ \ \ \ <span\ class="banner-tag">馃弳\ 绔炴妧娓告垙</span>\n\ \ \ \ \ \ <span\ class="banner-tag">馃幆\ 灏勫嚮娓告垙</span>\n\ \ \ \ \ \ <span\ class="banner-tag">馃實\ 寮€鏀句笘鐣\?/span>\n\ \ \ \ </div>\n\ \ </section>\n\n\ \ <div\ class="container">\n\ \ \ \ <!--\ 鐑棬娓告垙\ -->\n\ \ \ \ <section\ id="news">\n\ \ \ \ \ \ <h2\ class="section-title">馃幃\ 鐑棬娓告垙\ <span\ class="hot">HOT</span>\ <a\ href="\#"\ class="more">鏌ョ湅鏇村\ &raquo;</a></h2>\n\ \ \ \ \ \ <div\ class="game-grid">\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/zh/thumb/a/a1/Black_Myth_Wukong\.jpg/440px-Black_Myth_Wukong\.jpg"\ alt="榛戠璇濓細鎮熺┖"><span\ class="score">9\.8</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">榛戠璇濓細鎮熺┖</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-action">鍔ㄤ綔鍐掗櫓</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍥戒骇3A澶т綔锛屽熀浜庝腑鍥藉彜鍏稿悕钁椼€婅タ娓歌銆嬫敼缂栥€傜帺瀹舵壆婕斿瓩鎮熺┖锛屼娇鐢ㄥ鎰忛噾绠嶆涓庡悇绉嶅鎬垬鏂椼€傛父鎴忎互鍏剁簿缇庣殑鐢婚潰鍜屾祦鐣呯殑鎴樻枟绯荤粺钁楃О銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.8鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2024骞\?鏈\?0鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛氭父鎴忕瀛\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/b/b6/Elden_Ring_Box_art\.jpg/440px-Elden_Ring_Box_art\.jpg"\ alt="鑹惧皵鐧绘硶鐜\?><span\ class="score">9\.7</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鑹惧皵鐧绘硶鐜細榛勯噾鏍戝菇褰\?/div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-rpg">鍔ㄤ綔RPG</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">FromSoftware寮€鍙戯紝涔旀不路椹竵鍙備笌涓栫晫瑙傛瀯寤恒€傜帺瀹跺湪榛勯噾鏍戝穿濉屽悗鐨勬贩涔变笘鐣屼腑鎺㈢储锛屾寫鎴樺己澶OSS锛屾敹闆嗚澶囦笌鎴樻妧銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.7鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2024骞\?鏈\?1鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欶romSoftware</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/9/9f/Baldur%27s_Gate_3_cover\.jpg/440px-Baldur%27s_Gate_3_cover\.jpg"\ alt="鍗氬痉涔嬮棬3"><span\ class="score">9\.6</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鍗氬痉涔嬮棬3</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-rpg">RPG</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鎷夊皵妫伐浣滃寮€鍙戯紝DnD妗屾父瑙勫垯鏀圭紪銆傜帺瀹跺垱寤鸿鑹茬粍闃燂紝缁忓巻鍙茶瘲绾у啋闄╂梾绋嬨€傛父鎴忓寘鍚珮搴﹁嚜鐢辩殑瀵硅瘽绯荤粺鍜屾垬鏈€ф垬鏂椼€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.6鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2023骞\?鏈\?鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛歀arian\ Studios</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/0/00/Cyberpunk_2077_box_art\.jpg/440px-Cyberpunk_2077_box_art\.jpg"\ alt="璧涘崥鏈嬪厠2077"><span\ class="score">9\.2</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">璧涘崥鏈嬪厠2077锛氬線鏃ヤ箣褰\?/div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-adventure">鍐掗櫓</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">CDPR寮€鍙戠殑璧涘崥鏈嬪厠棰樻潗RPG璧勬枡鐗囥€備互鐗瑰伐瑙嗚鍦ㄥ鍩庡湴涓嬩笘鐣屽睍寮€鍐掗櫓锛屾柊澧炲啗浜嬬骇姝﹀櫒鍜岃浇鍏锋垬鏂楃郴缁熴€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.2鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2023骞\?鏈\?6鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欳D\ Projekt\ Red</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/4/4f/Forza_Horizon_5_cover\.jpg/440px-Forza_Horizon_5_cover\.jpg"\ alt="鏋侀檺绔為€燂細鍦板钩绾\?"><span\ class="score">9\.4</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鏋侀檺绔為€燂細鍦板钩绾\?</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-strategy">绔為€\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">Playground\ Games寮€鍙戠殑寮€鏀句笘鐣岃禌杞︽父鎴忋€傜帺瀹跺湪澧ㄨタ鍝ラ鎯呯殑楂橀€熷叕璺笂鑷敱椹伴獘锛屾敹闆嗚溅杈嗭紝鏀硅璋冩牎锛屽弬鍔燜estival璧涗簨銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.4鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2021骞\?1鏈\?鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛歅layground\ Games</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/2/2f/Hogwarts_Legacy_Cover\.jpg/440px-Hogwarts_Legacy_Cover\.jpg"\ alt="闇嶆牸娌冭尐涔嬮仐"><span\ class="score">9\.1</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">闇嶆牸娌冭尐涔嬮仐</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-adventure">鍐掗櫓</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍩轰簬JK缃楃惓榄旀硶涓栫晫IP鐨勫紑鏀句笘鐣屽啋闄╂父鎴忥紝鐜╁鍙帰绱㈤湇鏍兼矁鑼ㄥ煄鍫″強鍛ㄨ竟鍦板尯銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.1鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2023骞\?鏈\?0鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欰valanche\ Software</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/1/1f/Call_of_Duty_Modern_Warfare_III_2023_cover\.jpg/440px-Call_of_Duty_Modern_Warfare_III_2023_cover\.jpg"\ alt="浣垮懡鍙敜锛氱幇浠ｆ垬浜\?"><span\ class="score">9\.3</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">浣垮懡鍙敜锛氱幇浠ｆ垬浜\?</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-shooter">灏勫嚮</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍔ㄨ鍙戣鐨勭粡鍏窮PS绯诲垪鏈€鏂颁綔銆傜户缁幇浠ｆ垬浜夋晠浜嬬嚎锛屾櫘鑾辨柉涓婂皦甯﹂槦瀵规姉淇勭綏鏂瀬绔粍缁囷紝浣撻獙鐢靛奖绾ф垬鏂椾綋楠屻€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.3鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2023骞\?1鏈\?0鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欰ctivision</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/6/6e/Resident_Evil_4_%282023%29_cover\.jpg/440px-Resident_Evil_4_%282023%29_cover\.jpg"\ alt="鐢熷寲鍗辨満4锛氶噸鍒剁増"><span\ class="score">9\.0</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鐢熷寲鍗辨満4锛氶噸鍒剁増</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-horror">鎭愭€\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">Capcom缁忓吀鎭愭€栨父鎴忓畬鍏ㄩ噸鍒躲€傞噷鏄偮稴路鑲凹杩墠寰€娆ф床鏉戣惤钀ユ晳鎬荤粺鍗冮噾锛屽鎶楄鏉戞皯鎰熸煋鐨勪抚灏革紝浣撻獙绱у紶鍒烘縺鐨勭敓瀛樻亹鎬栥€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.0鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2023骞\?鏈\?4鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欳apcom</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/5/53/God_of_War_Ragnar%C3%B6k_cover_art\.jpg/440px-God_of_War_Ragnar%C3%B6k_cover_art\.jpg"\ alt="鎴樼5"><span\ class="score">9\.3</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鎴樼5锛氳绁為粍鏄\?/div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-action">鍔ㄤ綔鍐掗櫓</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍦ｈ帿灏煎崱宸ヤ綔瀹ゅ嚭鍝侊紝濂庢墭鏂笌鍎垮瓙闃跨壒鏌旀柉鍏卞悓瀵规姉鍖楁璇哥銆傛垬鏂楃郴缁熷叏闈㈣繘鍖栵紝鍓ф儏闇囨捈浜哄績銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.3鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2022骞\?1鏈\?鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛歋anta\ Monica\ Studio</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/a/a7/Final_Fantasy_VII_Rebirth_box_art\.jpg/440px-Final_Fantasy_VII_Rebirth_box_art\.jpg"\ alt="鏈€缁堝够鎯\?锛氶噸鐢\?><span\ class="score">9\.2</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">鏈€缁堝够鎯\?锛氶噸鐢\?/div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-rpg">RPG</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍙插厠濞佸皵路鑹惧凹鍏嬫柉閲嶅埗鐗堜笁閮ㄦ洸绗簩浣溿€傚厠鍔冲痉涓€琛岄€冪绫冲痉鍔狅紝鍓嶅線鏇村箍闃旂殑寮€鏀句笘鐣屽睍寮€鍐掗櫓銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?9\.2鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2024骞\?鏈\?9鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛歋quare\ Enix</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="game-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-cover"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/e/e3/Dragon%27s_Dogma_2_cover\.jpg/440px-Dragon%27s_Dogma_2_cover\.jpg"\ alt="榫欎箣淇℃潯2"><span\ class="score">8\.8</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="game-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-title">榫欎箣淇℃潯2</div>\n\ \ \ \ \ \ \ \ \ \ \ \ <span\ class="game-tag\ tag-action">鍔ㄤ綔RPG</span>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="game-desc">鍗℃櫘绌烘帹鍑虹殑寮€鏀句笘鐣屽姩浣淩PG銆傜帺瀹跺垱寤虹嫭鏈夎亴涓氾紝鎺㈢储绁炵澶ч檰锛屼笌闅忎粠涓€璧疯浼愬ぇ鍨嬫€墿銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>猸\?8\.8鍒\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>2024骞\?鏈\?2鏃\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="game-meta"\ style="margin-top:5px;">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>寮€鍙戝晢锛欳apcom</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\n\ \ \ \ <!--\ 鏈€鏂拌祫璁\?-->\n\ \ \ \ <section>\n\ \ \ \ \ \ <h2\ class="section-title">馃摪\ 鏈€鏂拌祫璁\?<span\ class="new">NEW</span>\ <a\ href="\#"\ class="more">鏌ョ湅鏇村\ &raquo;</a></h2>\n\ \ \ \ \ \ <div\ class="news-list">\n\ \ \ \ \ \ \ \ <div\ class="news-item">\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-thumb"><img\ src="https://upload\.wikimedia\.org/wikipedia/zh/thumb/a/a1/Black_Myth_Wukong\.jpg/440px-Black_Myth_Wukong\.jpg"\ alt="榛戠璇\?><span\ class="type-tag">鏂伴椈</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-content">\n\ \ \ \ \ \ \ \ \ \ \ \ <h3\ class="news-title"><a\ href="\#">銆婇粦绁炶瘽锛氭偀绌恒€婦LC姝ｅ湪寮€鍙戜腑锛屾垨灏\?025骞村彂甯\?/a></h3>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="news-desc">娓告垙绉戝鍒涘浜哄啹楠ラ€忛湶锛屾父鎴忕殑棣栦釜DLC姝ｅ湪绉瀬寮€鍙戜腑銆傛嵁鎮夋柊鍐呭灏嗗甫鏉ュ叏鏂扮殑鍓ф儏鍜孊OSS鎴橈紝鐜╁灏嗕綋楠屾洿澶氳タ娓歌鏁呬簨涓殑缁忓吀鍦烘櫙銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="news-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃搮\ 2026-05-30</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃憗锔\?12\.8涓囬槄璇\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃挰\ 3\.2涓囪瘎璁\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="news-item">\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-thumb"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/b/b6/Elden_Ring_Box_art\.jpg/440px-Elden_Ring_Box_art\.jpg"\ alt="鑹惧皵鐧绘硶鐜\?><span\ class="type-tag">鏀荤暐</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-content">\n\ \ \ \ \ \ \ \ \ \ \ \ <h3\ class="news-title"><a\ href="\#">銆婅壘灏旂櫥娉曠幆銆嬮粍閲戞爲骞藉奖\ 鍏˙OSS閫冭鎵撴硶鍚堥泦</a></h3>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="news-desc">璧勬枡鐗囨柊澧炲浣嶅己鍔汢OSS锛屾湰鏀荤暐姹囨€讳簡鍚凚OSS鐨勭畝鍗曟墦娉曡鐐癸紝鍗充娇鏂版墜涔熻兘椤哄埄閫氬叧銆傚寘鍚┛鍒鸿€呮\ GB銆佷孩閲戞槦杈夈€侀緳瑁呭ぇ鏍戝畧鍗瓑鏀荤暐銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="news-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃搮\ 2026-05-29</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃憗锔\?8\.9涓囬槄璇\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃挰\ 1\.8涓囪瘎璁\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="news-item">\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-thumb"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/9/9f/Baldur%27s_Gate_3_cover\.jpg/440px-Baldur%27s_Gate_3_cover\.jpg"\ alt="鍗氬痉涔嬮棬3"><span\ class="type-tag">鏇存柊</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-content">\n\ \ \ \ \ \ \ \ \ \ \ \ <h3\ class="news-title"><a\ href="\#">銆婂崥寰蜂箣闂\?銆嬬儹淇ˉ涓佸彂甯冿紝淇20浣欓」bug</a></h3>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="news-desc">Larian\ Studios浠婃棩鍙戝竷浜嗘父鎴忕儹淇ˉ涓侊紝涓昏淇浜嗛儴鍒嗙帺瀹跺弽棣堢殑宕╂簝闂浠ュ強鎴樻枟骞宠　璋冩暣銆備慨澶嶄簡閲庤洰浜鸿亴涓氱媯鏆寸姸鎬佸紓甯搁棶棰樸€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="news-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃搮\ 2026-05-28</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃憗锔\?5\.4涓囬槄璇\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃挰\ 8921璇勮</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="news-item">\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-thumb"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/a/a3/Steam_logo\.svg/200px-Steam_logo\.svg\.png"\ alt="Steam"><span\ class="type-tag">鎶樻墸</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-content">\n\ \ \ \ \ \ \ \ \ \ \ \ <h3\ class="news-title"><a\ href="\#">Steam澶忓澶т績鍗冲皢寮€鍚紝杩欎簺娓告垙鍊煎緱鏈熷緟</a></h3>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="news-desc">Steam澶忓淇冮攢灏嗕簬6鏈堝紑骞曪紝鍖呮嫭銆婇湇鏍兼矁鑼ㄤ箣閬椼€嬨€婅禌鍗氭湅鍏\?077銆嬪湪鍐呯殑澶氭娓告垙閮藉皢杩庢潵鍙蹭綆浠锋牸銆傚眾鏃惰繕鏈夋弧鍑忎紭鎯犲埜娲诲姩銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="news-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃搮\ 2026-05-27</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃憗锔\?15\.2涓囬槄璇\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃挰\ 4\.1涓囪瘎璁\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="news-item">\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-thumb"><img\ src="https://upload\.wikimedia\.org/wikipedia/en/thumb/2/23/Take-Two_Interactive_Logo\.svg/200px-Take-Two_Interactive_Logo\.svg\.png"\ alt="GTA6"><span\ class="type-tag">鍓嶇灮</span></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="news-content">\n\ \ \ \ \ \ \ \ \ \ \ \ <h3\ class="news-title"><a\ href="\#">銆奊TA6銆嬫寮忓畼瀹\?026骞寸瀛ｅ彂鍞紝棰勫憡鐗囪В鏋\?/a></h3>\n\ \ \ \ \ \ \ \ \ \ \ \ <p\ class="news-desc">R鏄熸寮忓甯冦€婁緺鐩楃寧杞︽墜6銆嬪皢浜\?026骞寸瀛ｇ櫥闄哖S5鍜孹box\ Series\ X\|S銆傞鍛婄墖灞曠ず鐨刅ICE\ CITY鐢婚潰寮曞彂鍏ㄧ悆鐜╁鐑銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="news-meta">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃搮\ 2026-05-26</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃憗锔\?28\.6涓囬槄璇\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span>馃挰\ 6\.8涓囪瘎璁\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\n\ \ \ \ <!--\ 鏀荤暐涓績\ -->\n\ \ \ \ <section\ id="strategy">\n\ \ \ \ \ \ <h2\ class="section-title">馃摉\ 鏀荤暐涓績\ <a\ href="\#"\ class="more">鏌ョ湅鏇村\ &raquo;</a></h2>\n\ \ \ \ \ \ <div\ class="strategy-section">\n\ \ \ \ \ \ \ \ <div\ class="strategy-main">\n\ \ \ \ \ \ \ \ \ \ <h3\ style="color:\#fff;margin-bottom:20px;">馃敟\ 鏈懆鐑棬鏀荤暐</h3>\n\ \ \ \ \ \ \ \ \ \ <div\ class="strategy-item">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>銆婇粦绁炶瘽锛氭偀绌恒€嬪叏BOSS鎵撴硶鏀荤暐锛堝惈绮鹃瓌鎺ㄨ崘锛\?/h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鏈枃姹囨€讳簡娓告垙鍏ㄩ儴BOSS鐨勮缁嗘墦娉曪紝鍖呮嫭灞炴€у厠鍒躲€佹鍣ㄩ€夋嫨銆佹垬鎶€鎼厤銆傚嵆浣挎槸鎵嬫畫鐜╁涔熻兘鎵惧埌閫傚悎鑷繁鐨勯€氬叧鏂规銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="step">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="step-num">1</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ style="color:\#888;font-size:0\.85em;">浜嗚ВBOSS鏀诲嚮瑙勫緥</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="step">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="step-num">2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ style="color:\#888;font-size:0\.85em;">閫夋嫨鍚堥€傜殑绁為€氬拰妫嶆硶</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="step">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="step-num">3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ style="color:\#888;font-size:0\.85em;">鍚堢悊鍒╃敤绮鹃瓌绯荤粺</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="strategy-item">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>銆婅壘灏旂櫥娉曠幆銆嬮粍閲戞爲骞藉奖\ 瀵嗘妧浣嶇疆澶у叏</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鏀堕泦鎵€鏈夎祼绂忕偣闄勮繎鐨勯殣钘忓瘑鎶€锛屽涔犲け钀界殑鍙ら緳鑱屼笟鎶€鑳姐€傛柊鐗堟湰鏂板7涓瘑鎶€鍒嗗竷鍦ㄥ菇褰变箣鍦扮殑鍚勪釜瑙掕惤銆\?/p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="strategy-item">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>銆婂崥寰蜂箣闂\?銆嬫渶浣宠亴涓氱粍鍚堟帹鑽\?/h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>璇︾粏鍒嗘瀽鍚勮亴涓氱壒鐐瑰拰鍗忓悓鏁堟灉锛屾帹鑽愬嚑濂楃粡杩囬獙璇佺殑寮哄姏缁勫悎銆傚寘鍚墿鐞嗛槦銆佹硶鏈槦銆佸弻浜哄皬闃熺瓑澶氱Build鏂规銆\?/p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ <div\ class="strategy-sidebar">\n\ \ \ \ \ \ \ \ \ \ <div\ class="side-card">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>馃弳\ 鏀荤暐鐑害姒\?/h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="side-num">1</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-content">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>榛戠璇濆叏BOSS鎵撴硶</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐑害\ 98\.5涓\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="side-num">2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-content">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>娉曠幆DLC閫冭鎵撴硶</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐑害\ 76\.2涓\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="side-num">3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-content">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鍗氬痉涔嬮棬3鑱屼笟鎺ㄨ崘</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐑害\ 54\.8涓\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="side-num">4</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="side-content">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>璧涘崥鏈嬪厠2077娴佹淳</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐑害\ 43\.1涓\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\n\ \ \ \ <!--\ 娓告垙宸ュ叿\ -->\n\ \ \ \ <section\ id="tools">\n\ \ \ \ \ \ <h2\ class="section-title">馃敡\ 娓告垙宸ュ叿\ <a\ href="\#"\ class="more">鏌ョ湅鏇村\ &raquo;</a></h2>\n\ \ \ \ \ \ <div\ class="tools-grid">\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃摑</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>CE淇敼鍣\?7\.5</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鏀寔1000\+娓告垙鐨勫唴瀛樹慨鏀瑰伐鍏穦鏇存柊鑷虫渶鏂扮増</p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃摝</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>3DM姹夊寲琛ヤ竵</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>涓绘祦3A澶т綔绠€浣撲腑鏂囨眽鍖栧寘\|鎸佺画鏇存柊涓\?/p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃帹</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>ReShade鐢婚潰澧炲己</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鎻愬崌娓告垙鐢昏川琛ㄧ幇\|鏀寔鑷畾涔夋护闀\?/p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃捑</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>浜戝瓨妗ｇ瀹\?/h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>浜戠鍚屾瀛樻。鏁版嵁\|闃叉瀛樻。涓㈠け</p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">鈿\?/div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>UU鍔犻€熷櫒</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>闄嶄綆娓告垙寤惰繜涓㈠寘\|鏀寔涓绘満鍜孭C</p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃枼锔\?/div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>甯х巼瑙ｉ攣宸ュ叿</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>瑙ｉ櫎娓告垙甯ф暟涓婇檺\|鏀寔Vulkan鍜孌X12</p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃搵</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>Steam璺宠烦涔\?/h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>瑙ｅ喅Steam鏃犳硶鐧诲綍\|steamcommunity\.com璁块棶</p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="tool-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-icon">馃敡</div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="tool-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>娓告垙淇宸ュ叿</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>淇娓告垙鎶ラ敊銆侀棯閫€銆佺己灏慏LL绛夐棶棰\?/p>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ <button\ class="tool-download">涓嬭浇</button>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\n\ \ \ \ <!--\ 鎺掕姒\?-->\n\ \ \ \ <section\ id="ranking">\n\ \ \ \ \ \ <h2\ class="section-title">馃弳\ 鎺掕姒\?/h2>\n\ \ \ \ \ \ <div\ class="ranking-section">\n\ \ \ \ \ \ \ \ <div\ class="ranking-card">\n\ \ \ \ \ \ \ \ \ \ <h4>馃敟\ 鏈懆鐑帺姒\?/h4>\n\ \ \ \ \ \ \ \ \ \ <div\ class="ranking-list">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-1">1</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>榛戠璇濓細鎮熺┖</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鍔ㄤ綔鍐掗櫓\ \|\ 鍥戒骇涔嬪厜</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">152涓\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-2">2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鑹惧皵鐧绘硶鐜\?/h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鍔ㄤ綔RPG\ \|\ 缁忓吀缁綔</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">98涓\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-3">3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>闇嶆牸娌冭尐涔嬮仐</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鍐掗櫓\ \|\ 榄旀硶涓栫晫</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">89涓\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">4</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鍗氬痉涔嬮棬3</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>CRPG\ \|\ 缁忓吀鍥炲綊</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">67涓\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">5</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>浣垮懡鍙敜</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>灏勫嚮\ \|\ 缁忓吀IP</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">54涓\?/span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="ranking-card">\n\ \ \ \ \ \ \ \ \ \ <h4>猸\?璇勫垎鎺掕</h4>\n\ \ \ \ \ \ \ \ \ \ <div\ class="ranking-list">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-1">1</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>榛戠璇濓細鎮熺┖</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐢婚潰銆佹垬鏂楀潎涓洪《绾ф按鍑\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">9\.8</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-2">2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鑹惧皵鐧绘硶鐜\?/h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>寮€鏀句笘鐣岃璁＄簿濡\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">9\.7</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-3">3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鍗氬痉涔嬮棬3</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鍓ф湰璐ㄩ噺鏋侀珮</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">9\.6</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">4</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鍦板钩绾\?</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鐢婚潰琛ㄧ幇鎯婅壋</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">9\.4</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">5</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鎴樼5</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>鎴樻枟绯荤粺鍑鸿壊</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">9\.3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="ranking-card">\n\ \ \ \ \ \ \ \ \ \ <h4>馃搱\ 涓婂崌鏈€蹇\?/h4>\n\ \ \ \ \ \ \ \ \ \ <div\ class="ranking-list">\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-1">1</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>GTA6</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>\+38鍚\?\|\ 鍙戝敭棰勬湡鍗囨俯</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">鈫\?8</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-2">2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鎬墿鐚庝汉锛氳崚閲\?/h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>\+25鍚\?\|\ 娴嬭瘯鐗堜笂绾\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">鈫\?5</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-3">3</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>姝讳骸鎼佹祬2</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>\+18鍚\?\|\ 鏂伴鍛婂叕寮€</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">鈫\?8</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">4</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>鏈€缁堝够鎯\?锛氶噸鐢\?/h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>\+12鍚\?\|\ PC鐗堥鏈\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">鈫\?2</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="ranking-item">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-num\ rank-other">5</span>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <div\ class="rank-info">\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <h5>榫欎箣淇℃潯2</h5>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ <p>\+8鍚\?\|\ 澶忓淇冮攢</p>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ \ \ \ \ <span\ class="rank-value">鈫\?</span>\n\ \ \ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\n\ \ \ \ <!--\ 纭欢璇勬祴\ -->\n\ \ \ \ <section\ id="hardware">\n\ \ \ \ \ \ <h2\ class="section-title">馃枼锔\?纭欢璇勬祴\ <a\ href="\#"\ class="more">鏌ョ湅鏇村\ &raquo;</a></h2>\n\ \ \ \ \ \ <div\ class="hardware-grid">\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/4/43/PlayStation_5_console_and_controller\.png/440px-PlayStation_5_console_and_controller\.png"\ alt="PS5"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>PlayStation\ 5\ Pro</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>绱㈠凹鏈€鏂版父鎴忎富鏈猴紝鎼浇鍗囩骇鐗圙PU锛屾敮鎸\?K杈撳嚭鍜屽厜绾胯拷韪寮恒€傛帹鑽愯拷姹傛瀬鑷寸敾璐ㄧ殑鐜╁鍏ユ墜銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼4499\ <del>楼4999</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/2/21/Nvidia_logo\.svg/440px-Nvidia_logo\.svg\.png"\ alt="RTX\ 5080"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>RTX\ 5080\ 鏄惧崱</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>NVIDIA鏂颁竴浠ｆ棗鑸版樉鍗★紝Blackwell鏋舵瀯锛\?2GB\ GDDR7鏄惧瓨锛孉I绠楀姏澶у箙鎻愬崌锛\?K娓告垙棣栭€夈€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼8999\ <del>楼9999</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/4/43/Xbox-Series-X-Console-wController\.png/440px-Xbox-Series-X-Console-wController\.png"\ alt="Xbox\ Series\ X"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>Xbox\ Series\ X</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>寰蒋鏈€寮轰富鏈猴紝12\ TFLOPS\ GPU锛\?TB\ SSD鏋侀€熷姞杞姐€侴ame\ Pass璁㈤槄瓒呭€硷紝鐣呯帺鐧炬澶т綔銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼3599\ <del>楼3999</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/4/43/Razer_logo\.svg/440px-Razer_logo\.svg\.png"\ alt="Razer"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>闆疯泧榛戝濡嘨4\ Pro</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鏃楄埌鏈烘閿洏锛孏asket缁撴瀯璁捐锛岀儹鎻掓嫈杞翠綋锛屾敮鎸\?\.4GHz鏃犵嚎鍜岃摑鐗欙紝RGB鐏晥鐐叿銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼1299\ <del>楼1499</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/2/23/Logitech_logo\.svg/440px-Logitech_logo\.svg\.png"\ alt="Logitech"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>缃楁妧\ G\ PRO\ X\ SUPERLIGHT\ 3</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>椤剁骇鏃犵嚎娓告垙榧犳爣锛岄噸閲忎粎60g锛孒ero\ 25K浼犳劅鍣紝缁埅闀胯揪90灏忔椂锛岀數绔為€夋墜棣栭€夈€\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼899\ <del>楼999</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\n\ \ \ \ \ \ \ \ <div\ class="hardware-card">\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-img"><img\ src="https://upload\.wikimedia\.org/wikipedia/commons/thumb/e/e8/Sony_logo\.svg/440px-Sony_logo\.svg\.png"\ alt="Sony"></div>\n\ \ \ \ \ \ \ \ \ \ <div\ class="hardware-info">\n\ \ \ \ \ \ \ \ \ \ \ \ <h4>绱㈠凹\ WH-1000XM6</h4>\n\ \ \ \ \ \ \ \ \ \ \ \ <p>鏃楄埌闄嶅櫔鑰虫満锛屽崌绾х増涓诲姩闄嶅櫔锛岄煶璐ㄥ嚭鑹诧紝浣╂埓鑸掗€傦紝閫傚悎闀挎椂闂存父鎴忓拰闊充箰娆ｈ祻銆\?/p>\n\ \ \ \ \ \ \ \ \ \ \ \ <div\ class="hardware-price">楼2999\ <del>楼3499</del></div>\n\ \ \ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ \ \ </div>\n\ \ \ \ \ \ </div>\n\ \ \ \ </section>\n\ \ </div>\n\n\ \ <footer>\n\ \ \ \ <div\ class="footer-main">\n\ \ \ \ \ \ <div\ class="footer-about">\n\ \ \ \ \ \ \ \ <div\ class="logo">3DM<span>娓告垙缃\?/span></div>\n\ \ \ \ \ \ \ \ <p>3DM娓告垙缃戝垱寤轰簬2009骞达紝鏄浗鍐呯煡鍚嶇殑娓告垙缁煎悎闂ㄦ埛缃戠珯銆傝嚧鍔涗簬涓虹帺瀹舵彁渚涙渶鏂版渶蹇殑娓告垙璧勮銆佹渶鍏ㄦ渶寮虹殑娓告垙鏀荤暐銆佹渶涓撲笟渚挎嵎鐨勬父鎴忓伐鍏枫€\?/p>\n\ \ \ \ \ \ </div>\n\ \ \ \ \ \ <div\ class="footer-col">\n\ \ \ \ \ \ \ \ <h4>娓告垙鍒嗙被</h4>\n\ \ \ \ \ \ \ \ <a\ href="\#">鍔ㄤ綔鍐掗櫓</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">瑙掕壊鎵紨</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">灏勫嚮娓告垙</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">绛栫暐缁忚惀</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">浣撹偛绔炴妧</a>\n\ \ \ \ \ \ </div>\n\ \ \ \ \ \ <div\ class="footer-col">\n\ \ \ \ \ \ \ \ <h4>鐑棬娓告垙</h4>\n\ \ \ \ \ \ \ \ <a\ href="\#">榛戠璇濓細鎮熺┖</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">鑹惧皵鐧绘硶鐜\?/a>\n\ \ \ \ \ \ \ \ <a\ href="\#">鍗氬痉涔嬮棬3</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">璧涘崥鏈嬪厠2077</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">GTA6</a>\n\ \ \ \ \ \ </div>\n\ \ \ \ \ \ <div\ class="footer-col">\n\ \ \ \ \ \ \ \ <h4>鍏充簬鎴戜滑</h4>\n\ \ \ \ \ \ \ \ <a\ href="\#">鍏徃绠€浠\?/a>\n\ \ \ \ \ \ \ \ <a\ href="\#">鑱旂郴鏂瑰紡</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">鍔犲叆鎴戜滑</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">鐢ㄦ埛鍗忚</a>\n\ \ \ \ \ \ \ \ <a\ href="\#">闅愮鏀跨瓥</a>\n\ \ \ \ \ \ </div>\n\ \ \ \ </div>\n\ \ \ \ <div\ class="footer-bottom">\n\ \ \ \ \ \ <p>漏\ 2009-2026\ 3DM娓告垙缃\?All\ Rights\ Reserved\ \|\ <a\ href="\#">浜琁CP澶嘪XXXXXX鍙\?/a></p>\n\ \ \ \ </div>\n\ \ </footer>\n</body>\n</html>"
    }
  }
}

<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3DM游戏网 - 全球热门游戏攻略与资讯</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Microsoft YaHei', 'PingFang SC', sans-serif;
      background: #121212;
      color: #e0e0e0;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header */
    header {
      background: linear-gradient(90deg, #e74c3c, #c0392b);
      padding: 10px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 1.8em;
      font-weight: bold;
      color: #fff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }

    .logo span {
      color: #f39c12;
    }

    .header-nav {
      display: flex;
      gap: 25px;
    }

    .header-nav a {
      color: rgba(255,255,255,0.9);
      text-decoration: none;
      font-size: 0.95em;
      transition: color 0.3s;
    }

    .header-nav a:hover {
      color: #f39c12;
    }

    .search-box {
      display: flex;
      gap: 8px;
    }

    .search-box input {
      padding: 8px 15px;
      border: none;
      border-radius: 4px;
      background: rgba(255,255,255,0.95);
      color: #333;
      width: 200px;
    }

    .search-box button {
      padding: 8px 20px;
      background: #2c3e50;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    /* Banner */
    .banner {
      background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
      padding: 100px 40px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .banner::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: radial-gradient(circle at 30% 50%, rgba(231, 76, 60, 0.15) 0%, transparent 50%),
                  radial-gradient(circle at 70% 50%, rgba(243, 156, 18, 0.1) 0%, transparent 50%);
    }

    .banner h1 {
      font-size: 3.2em;
      margin-bottom: 15px;
      position: relative;
    }

    .banner h1 span {
      color: #e74c3c;
    }

    .banner p {
      font-size: 1.15em;
      color: #888;
      position: relative;
    }

    .banner-tags {
      margin-top: 25px;
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .banner-tag {
      padding: 6px 18px;
      border-radius: 20px;
      font-size: 0.9em;
      background: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.2);
      cursor: pointer;
      transition: all 0.3s;
    }

    .banner-tag:hover {
      background: #e74c3c;
      border-color: #e74c3c;
    }

    /* Container */
    .container {
      max-width: 1400px;
      margin: 0 auto;
      padding: 40px;
    }

    /* Section Title */
    .section-title {
      font-size: 1.5em;
      padding-bottom: 15px;
      border-bottom: 3px solid #e74c3c;
      margin-bottom: 30px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .section-title .hot {
      background: #e74c3c;
      color: #fff;
      font-size: 0.5em;
      padding: 3px 8px;
      border-radius: 3px;
    }

    .section-title .new {
      background: #2ecc71;
      color: #fff;
      font-size: 0.5em;
      padding: 3px 8px;
      border-radius: 3px;
    }

    .section-title .more {
      margin-left: auto;
      font-size: 0.6em;
      color: #888;
      font-weight: normal;
    }

    /* Game Grid */
    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 25px;
      margin-bottom: 60px;
    }

    .game-card {
      background: #1e1e1e;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s, box-shadow 0.3s;
      border: 1px solid #333;
    }

    .game-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.5);
      border-color: #e74c3c;
    }

    .game-cover {
      height: 180px;
      background: #2c3e50;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 4em;
      position: relative;
      overflow: hidden;
    }

    .game-cover img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .game-cover .emoji {
      position: relative;
      z-index: 1;
    }

    .game-cover .score {
      position: absolute;
      top: 10px;
      right: 10px;
      background: rgba(231, 76, 60, 0.9);
      color: #fff;
      padding: 3px 10px;
      border-radius: 4px;
      font-size: 0.85em;
      font-weight: bold;
      z-index: 2;
    }

    .game-info {
      padding: 20px;
    }

    .game-title {
      font-size: 1.2em;
      font-weight: bold;
      margin-bottom: 8px;
      color: #fff;
    }

    .game-tag {
      display: inline-block;
      padding: 3px 10px;
      border-radius: 4px;
      font-size: 0.75em;
      margin-bottom: 10px;
    }

    .tag-action { background: rgba(231, 76, 60, 0.2); color: #e74c3c; }
    .tag-rpg { background: rgba(155, 89, 182, 0.2); color: #9b59b6; }
    .tag-adventure { background: rgba(52, 152, 219, 0.2); color: #3498db; }
    .tag-strategy { background: rgba(46, 204, 113, 0.2); color: #2ecc71; }
    .tag-shooter { background: rgba(241, 196, 15, 0.2); color: #f1c40f; }
    .tag-horror { background: rgba(192, 57, 43, 0.2); color: #c0392b; }

    .game-desc {
      font-size: 0.9em;
      color: #888;
      line-height: 1.6;
      margin-bottom: 12px;
    }

    .game-meta {
      display: flex;
      justify-content: space-between;
      font-size: 0.85em;
      color: #666;
    }

    /* News List */
    .news-list {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-bottom: 60px;
    }

    .news-item {
      background: #1e1e1e;
      border-radius: 10px;
      padding: 25px;
      display: flex;
      gap: 20px;
      border: 1px solid #333;
      transition: border-color 0.3s;
    }

    .news-item:hover {
      border-color: #e74c3c;
    }

    .news-thumb {
      width: 200px;
      height: 130px;
      background: #2c3e50;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2.5em;
      flex-shrink: 0;
      position: relative;
      overflow: hidden;
    }

    .news-thumb img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .news-thumb .type-tag {
      position: absolute;
      top: 8px;
      left: 8px;
      padding: 2px 8px;
      border-radius: 3px;
      font-size: 0.7em;
      background: rgba(231, 76, 60, 0.9);
      color: #fff;
    }

    .news-content {
      flex: 1;
    }

    .news-title {
      font-size: 1.15em;
      font-weight: bold;
      margin-bottom: 10px;
      color: #fff;
    }

    .news-title a:hover {
      color: #e74c3c;
    }

    .news-desc {
      font-size: 0.9em;
      color: #888;
      margin-bottom: 12px;
      line-height: 1.7;
    }

    .news-meta {
      display: flex;
      gap: 20px;
      font-size: 0.85em;
      color: #666;
    }

    .news-meta span {
      display: flex;
      align-items: center;
      gap: 5px;
    }

    /* Strategy Section */
    .strategy-section {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 30px;
      margin-bottom: 60px;
    }

    .strategy-main {
      background: #1e1e1e;
      border-radius: 12px;
      padding: 25px;
      border: 1px solid #333;
    }

    .strategy-item {
      padding: 20px 0;
      border-bottom: 1px solid #333;
    }

    .strategy-item:last-child {
      border-bottom: none;
      padding-bottom: 0;
    }

    .strategy-item h4 {
      font-size: 1.1em;
      color: #fff;
      margin-bottom: 8px;
    }

    .strategy-item p {
      color: #888;
      font-size: 0.9em;
      line-height: 1.7;
    }

    .strategy-item .step {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-top: 10px;
    }

    .step-num {
      width: 24px;
      height: 24px;
      background: #e74c3c;
      color: #fff;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8em;
      font-weight: bold;
    }

    .strategy-sidebar .side-card {
      background: #1e1e1e;
      border-radius: 12px;
      padding: 20px;
      border: 1px solid #333;
      margin-bottom: 20px;
    }

    .strategy-sidebar h4 {
      font-size: 1em;
      color: #fff;
      margin-bottom: 15px;
      padding-bottom: 10px;
      border-bottom: 2px solid #e74c3c;
    }

    .side-item {
      display: flex;
      gap: 12px;
      padding: 12px 0;
      border-bottom: 1px solid #333;
    }

    .side-item:last-child {
      border-bottom: none;
    }

    .side-num {
      font-size: 1.5em;
      color: #e74c3c;
      font-weight: bold;
      width: 30px;
    }

    .side-content h5 {
      font-size: 0.95em;
      color: #fff;
      margin-bottom: 4px;
    }

    .side-content p {
      font-size: 0.8em;
      color: #666;
    }

    /* Tools Section */
    .tools-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-bottom: 60px;
    }

    .tool-card {
      background: #1e1e1e;
      border-radius: 10px;
      padding: 20px;
      border: 1px solid #333;
      display: flex;
      align-items: center;
      gap: 15px;
      transition: all 0.3s;
    }

    .tool-card:hover {
      border-color: #e74c3c;
      background: #252525;
    }

    .tool-icon {
      width: 50px;
      height: 50px;
      background: linear-gradient(135deg, #e74c3c, #c0392b);
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.5em;
    }

    .tool-info {
      flex: 1;
    }

    .tool-info h4 {
      font-size: 1em;
      margin-bottom: 5px;
      color: #fff;
    }

    .tool-info p {
      font-size: 0.85em;
      color: #666;
    }

    .tool-download {
      padding: 8px 15px;
      background: #e74c3c;
      color: #fff;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 0.85em;
      transition: background 0.3s;
    }

    .tool-download:hover {
      background: #c0392b;
    }

    /* Ranking Section */
    .ranking-section {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
      margin-bottom: 60px;
    }

    .ranking-card {
      background: #1e1e1e;
      border-radius: 12px;
      padding: 25px;
      border: 1px solid #333;
    }

    .ranking-card h4 {
      font-size: 1.1em;
      color: #fff;
      margin-bottom: 20px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .ranking-list {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .ranking-item {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 10px;
      border-radius: 8px;
      transition: background 0.3s;
    }

    .ranking-item:hover {
      background: #252525;
    }

    .rank-num {
      width: 28px;
      height: 28px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 6px;
      font-weight: bold;
      font-size: 0.9em;
    }

    .rank-1 { background: linear-gradient(135deg, #f39c12, #e67e22); color: #fff; }
    .rank-2 { background: linear-gradient(135deg, #95a5a6, #7f8c8d); color: #fff; }
    .rank-3 { background: linear-gradient(135deg, #cd6133, #a04000); color: #fff; }
    .rank-other { background: #333; color: #888; }

    .rank-info {
      flex: 1;
    }

    .rank-info h5 {
      font-size: 0.95em;
      color: #fff;
      margin-bottom: 2px;
    }

    .rank-info p {
      font-size: 0.8em;
      color: #666;
    }

    .rank-value {
      font-size: 0.85em;
      color: #e74c3c;
      font-weight: bold;
    }

    /* Hardware Section */
    .hardware-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 25px;
      margin-bottom: 60px;
    }

    .hardware-card {
      background: #1e1e1e;
      border-radius: 12px;
      overflow: hidden;
      border: 1px solid #333;
      transition: all 0.3s;
    }

    .hardware-card:hover {
      border-color: #e74c3c;
      transform: translateY(-3px);
    }

    .hardware-img {
      height: 160px;
      background: #2c3e50;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 3em;
      overflow: hidden;
    }

    .hardware-img img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .hardware-info {
      padding: 20px;
    }

    .hardware-info h4 {
      font-size: 1.1em;
      color: #fff;
      margin-bottom: 8px;
    }

    .hardware-info p {
      font-size: 0.85em;
      color: #888;
      margin-bottom: 12px;
      line-height: 1.6;
    }

    .hardware-price {
      font-size: 1.3em;
      color: #e74c3c;
      font-weight: bold;
    }

    .hardware-price del {
      font-size: 0.7em;
      color: #666;
      margin-left: 8px;
    }

    /* Footer */
    footer {
      background: #0a0a0a;
      padding: 50px 40px;
      border-top: 1px solid #333;
    }

    .footer-main {
      display: grid;
      grid-template-columns: 2fr 1fr 1fr 1fr;
      gap: 40px;
      max-width: 1400px;
      margin: 0 auto 30px;
    }

    .footer-about .logo {
      margin-bottom: 15px;
    }

    .footer-about p {
      color: #666;
      font-size: 0.9em;
      line-height: 1.8;
    }

    .footer-col h4 {
      color: #fff;
      margin-bottom: 20px;
      font-size: 1em;
    }

    .footer-col a {
      display: block;
      color: #666;
      font-size: 0.9em;
      margin-bottom: 12px;
      transition: color 0.3s;
    }

    .footer-col a:hover {
      color: #e74c3c;
    }

    .footer-bottom {
      text-align: center;
      padding-top: 30px;
      border-top: 1px solid #222;
      max-width: 1400px;
      margin: 0 auto;
    }

    .footer-bottom p {
      color: #555;
      font-size: 0.85em;
    }

    .footer-bottom a {
      color: #888;
    }

    .footer-bottom a:hover {
      color: #e74c3c;
    }

    /* Responsive */
    @media (max-width: 1024px) {
      .strategy-section {
        grid-template-columns: 1fr;
      }

      .ranking-section {
        grid-template-columns: 1fr;
      }

      .footer-main {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media (max-width: 768px) {
      .header-nav, .search-box {
        display: none;
      }

      .banner h1 {
        font-size: 2em;
      }

      .news-item {
        flex-direction: column;
      }

      .news-thumb {
        width: 100%;
        height: 150px;
      }

      header {
        padding: 15px 20px;
      }

      .container {
        padding: 20px;
      }

      .footer-main {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">3DM<span>游戏网</span></div>
    <nav class="header-nav">
      <a href="#">首页</a>
      <a href="#news">游戏资讯</a>
      <a href="#strategy">攻略中心</a>
      <a href="#tools">游戏工具</a>
      <a href="#ranking">排行榜</a>
      <a href="#hardware">硬件评测</a>
    </nav>
    <div class="search-box">
      <input type="text" placeholder="搜索游戏、攻略...">
      <button>搜索</button>
    </div>
  </header>

  <section class="banner" id="home">
    <h1>全球热门<span>游戏</span>一网打尽</h1>
    <p>第一时间获取游戏资讯、专业攻略、实用工具，与全球玩家一起畅玩</p>
    <div class="banner-tags">
      <span class="banner-tag">🎮 动作冒险</span>
      <span class="banner-tag">⚔️ 角色扮演</span>
      <span class="banner-tag">🏆 竞技游戏</span>
      <span class="banner-tag">🎯 射击游戏</span>
      <span class="banner-tag">🌍 开放世界</span>
    </div>
  </section>

  <div class="container">
    <!-- 热门游戏 -->
    <section id="news">
      <h2 class="section-title">🎮 热门游戏 <span class="hot">HOT</span> <a href="#" class="more">查看更多 &raquo;</a></h2>
      <div class="game-grid">
        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/zh/thumb/a/a1/Black_Myth_Wukong.jpg/440px-Black_Myth_Wukong.jpg" alt="黑神话：悟空"><span class="score">9.8</span></div>
          <div class="game-info">
            <div class="game-title">黑神话：悟空</div>
            <span class="game-tag tag-action">动作冒险</span>
            <p class="game-desc">国产3A大作，基于中国古典名著《西游记》改编。玩家扮演孙悟空，使用如意金箍棒与各种妖怪战斗。游戏以其精美的画面和流畅的战斗系统著称。</p>
            <div class="game-meta">
              <span>⭐ 9.8分</span>
              <span>2024年8月20日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：游戏科学</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/b6/Elden_Ring_Box_art.jpg/440px-Elden_Ring_Box_art.jpg" alt="艾尔登法环"><span class="score">9.7</span></div>
          <div class="game-info">
            <div class="game-title">艾尔登法环：黄金树幽影</div>
            <span class="game-tag tag-rpg">动作RPG</span>
            <p class="game-desc">FromSoftware开发，乔治·马丁参与世界观构建。玩家在黄金树崩塌后的混乱世界中探索，挑战强大BOSS，收集装备与战技。</p>
            <div class="game-meta">
              <span>⭐ 9.7分</span>
              <span>2024年6月21日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：FromSoftware</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9f/Baldur%27s_Gate_3_cover.jpg/440px-Baldur%27s_Gate_3_cover.jpg" alt="博德之门3"><span class="score">9.6</span></div>
          <div class="game-info">
            <div class="game-title">博德之门3</div>
            <span class="game-tag tag-rpg">RPG</span>
            <p class="game-desc">拉尔森工作室开发，DnD桌游规则改编。玩家创建角色组队，经历史诗级冒险旅程。游戏包含高度自由的对话系统和战术性战斗。</p>
            <div class="game-meta">
              <span>⭐ 9.6分</span>
              <span>2023年8月3日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Larian Studios</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/00/Cyberpunk_2077_box_art.jpg/440px-Cyberpunk_2077_box_art.jpg" alt="赛博朋克2077"><span class="score">9.2</span></div>
          <div class="game-info">
            <div class="game-title">赛博朋克2077：往日之影</div>
            <span class="game-tag tag-adventure">冒险</span>
            <p class="game-desc">CDPR开发的赛博朋克题材RPG资料片。以特工视角在夜城地下世界展开冒险，新增军事级武器和载具战斗系统。</p>
            <div class="game-meta">
              <span>⭐ 9.2分</span>
              <span>2023年9月26日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：CD Projekt Red</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/4f/Forza_Horizon_5_cover.jpg/440px-Forza_Horizon_5_cover.jpg" alt="极限竞速：地平线5"><span class="score">9.4</span></div>
          <div class="game-info">
            <div class="game-title">极限竞速：地平线5</div>
            <span class="game-tag tag-strategy">竞速</span>
            <p class="game-desc">Playground Games开发的开放世界赛车游戏。玩家在墨西哥风情的高速公路上自由驰骋，收集车辆，改装调校，参加Festival赛事。</p>
            <div class="game-meta">
              <span>⭐ 9.4分</span>
              <span>2021年11月5日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Playground Games</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/2f/Hogwarts_Legacy_Cover.jpg/440px-Hogwarts_Legacy_Cover.jpg" alt="霍格沃茨之遗"><span class="score">9.1</span></div>
          <div class="game-info">
            <div class="game-title">霍格沃茨之遗</div>
            <span class="game-tag tag-adventure">冒险</span>
            <p class="game-desc">基于JK罗琳魔法世界IP的开放世界冒险游戏，玩家可探索霍格沃茨城堡及周边地区。</p>
            <div class="game-meta">
              <span>⭐ 9.1分</span>
              <span>2023年2月10日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Avalanche Software</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/1f/Call_of_Duty_Modern_Warfare_III_2023_cover.jpg/440px-Call_of_Duty_Modern_Warfare_III_2023_cover.jpg" alt="使命召唤：现代战争3"><span class="score">9.3</span></div>
          <div class="game-info">
            <div class="game-title">使命召唤：现代战争3</div>
            <span class="game-tag tag-shooter">射击</span>
            <p class="game-desc">动视发行的经典FPS系列最新作。继续现代战争故事线，普莱斯上尉带队对抗俄罗斯极端组织，体验电影级战斗体验。</p>
            <div class="game-meta">
              <span>⭐ 9.3分</span>
              <span>2023年11月10日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Activision</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/6/6e/Resident_Evil_4_%282023%29_cover.jpg/440px-Resident_Evil_4_%282023%29_cover.jpg" alt="生化危机4：重制版"><span class="score">9.0</span></div>
          <div class="game-info">
            <div class="game-title">生化危机4：重制版</div>
            <span class="game-tag tag-horror">恐怖</span>
            <p class="game-desc">Capcom经典恐怖游戏完全重制。里昂·S·肯尼迪前往欧洲村落营救总统千金，对抗被村民感染的丧尸，体验紧张刺激的生存恐怖。</p>
            <div class="game-meta">
              <span>⭐ 9.0分</span>
              <span>2023年3月24日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Capcom</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/53/God_of_War_Ragnar%C3%B6k_cover_art.jpg/440px-God_of_War_Ragnar%C3%B6k_cover_art.jpg" alt="战神5"><span class="score">9.3</span></div>
          <div class="game-info">
            <div class="game-title">战神5：诸神黄昏</div>
            <span class="game-tag tag-action">动作冒险</span>
            <p class="game-desc">圣莫尼卡工作室出品，奎托斯与儿子阿特柔斯共同对抗北欧诸神。战斗系统全面进化，剧情震撼人心。</p>
            <div class="game-meta">
              <span>⭐ 9.3分</span>
              <span>2022年11月9日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Santa Monica Studio</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a7/Final_Fantasy_VII_Rebirth_box_art.jpg/440px-Final_Fantasy_VII_Rebirth_box_art.jpg" alt="最终幻想7：重生"><span class="score">9.2</span></div>
          <div class="game-info">
            <div class="game-title">最终幻想7：重生</div>
            <span class="game-tag tag-rpg">RPG</span>
            <p class="game-desc">史克威尔·艾尼克斯重制版三部曲第二作。克劳德一行逃离米德加，前往更广阔的开放世界展开冒险。</p>
            <div class="game-meta">
              <span>⭐ 9.2分</span>
              <span>2024年2月29日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Square Enix</span>
            </div>
          </div>
        </div>

        <div class="game-card">
          <div class="game-cover"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/e/e3/Dragon%27s_Dogma_2_cover.jpg/440px-Dragon%27s_Dogma_2_cover.jpg" alt="龙之信条2"><span class="score">8.8</span></div>
          <div class="game-info">
            <div class="game-title">龙之信条2</div>
            <span class="game-tag tag-action">动作RPG</span>
            <p class="game-desc">卡普空推出的开放世界动作RPG。玩家创建独有职业，探索神秘大陆，与随从一起讨伐大型怪物。</p>
            <div class="game-meta">
              <span>⭐ 8.8分</span>
              <span>2024年3月22日</span>
            </div>
            <div class="game-meta" style="margin-top:5px;">
              <span>开发商：Capcom</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 最新资讯 -->
    <section>
      <h2 class="section-title">📰 最新资讯 <span class="new">NEW</span> <a href="#" class="more">查看更多 &raquo;</a></h2>
      <div class="news-list">
        <div class="news-item">
          <div class="news-thumb"><img src="https://upload.wikimedia.org/wikipedia/zh/thumb/a/a1/Black_Myth_Wukong.jpg/440px-Black_Myth_Wukong.jpg" alt="黑神话"><span class="type-tag">新闻</span></div>
          <div class="news-content">
            <h3 class="news-title"><a href="#">《黑神话：悟空》DLC正在开发中，或将2025年发布</a></h3>
            <p class="news-desc">游戏科学创始人冯骥透露，游戏的首个DLC正在积极开发中。据悉新内容将带来全新的剧情和BOSS战，玩家将体验更多西游记故事中的经典场景。</p>
            <div class="news-meta">
              <span>📅 2026-05-30</span>
              <span>👁️ 12.8万阅读</span>
              <span>💬 3.2万评论</span>
            </div>
          </div>
        </div>

        <div class="news-item">
          <div class="news-thumb"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/b6/Elden_Ring_Box_art.jpg/440px-Elden_Ring_Box_art.jpg" alt="艾尔登法环"><span class="type-tag">攻略</span></div>
          <div class="news-content">
            <h3 class="news-title"><a href="#">《艾尔登法环》黄金树幽影 全BOSS逃课打法合集</a></h3>
            <p class="news-desc">资料片新增多位强力BOSS，本攻略汇总了各BOSS的简单打法要点，即使新手也能顺利通关。包含穿刺者梅 GB、亢金星辉、龙装大树守卫等攻略。</p>
            <div class="news-meta">
              <span>📅 2026-05-29</span>
              <span>👁️ 8.9万阅读</span>
              <span>💬 1.8万评论</span>
            </div>
          </div>
        </div>

        <div class="news-item">
          <div class="news-thumb"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9f/Baldur%27s_Gate_3_cover.jpg/440px-Baldur%27s_Gate_3_cover.jpg" alt="博德之门3"><span class="type-tag">更新</span></div>
          <div class="news-content">
            <h3 class="news-title"><a href="#">《博德之门3》热修补丁发布，修复20余项bug</a></h3>
            <p class="news-desc">Larian Studios今日发布了游戏热修补丁，主要修复了部分玩家反馈的崩溃问题以及战斗平衡调整。修复了野蛮人职业狂暴状态异常问题。</p>
            <div class="news-meta">
              <span>📅 2026-05-28</span>
              <span>👁️ 5.4万阅读</span>
              <span>💬 8921评论</span>
            </div>
          </div>
        </div>

        <div class="news-item">
          <div class="news-thumb"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a3/Steam_logo.svg/200px-Steam_logo.svg.png" alt="Steam"><span class="type-tag">折扣</span></div>
          <div class="news-content">
            <h3 class="news-title"><a href="#">Steam夏季大促即将开启，这些游戏值得期待</a></h3>
            <p class="news-desc">Steam夏季促销将于6月开幕，包括《霍格沃茨之遗》《赛博朋克2077》在内的多款游戏都将迎来史低价格。届时还有满减优惠券活动。</p>
            <div class="news-meta">
              <span>📅 2026-05-27</span>
              <span>👁️ 15.2万阅读</span>
              <span>💬 4.1万评论</span>
            </div>
          </div>
        </div>

        <div class="news-item">
          <div class="news-thumb"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/23/Take-Two_Interactive_Logo.svg/200px-Take-Two_Interactive_Logo.svg.png" alt="GTA6"><span class="type-tag">前瞻</span></div>
          <div class="news-content">
            <h3 class="news-title"><a href="#">《GTA6》正式官宣2026年秋季发售，预告片解析</a></h3>
            <p class="news-desc">R星正式宣布《侠盗猎车手6》将于2026年秋季登陆PS5和Xbox Series X|S。预告片展示的VICE CITY画面引发全球玩家热议。</p>
            <div class="news-meta">
              <span>📅 2026-05-26</span>
              <span>👁️ 28.6万阅读</span>
              <span>💬 6.8万评论</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 攻略中心 -->
    <section id="strategy">
      <h2 class="section-title">📖 攻略中心 <a href="#" class="more">查看更多 &raquo;</a></h2>
      <div class="strategy-section">
        <div class="strategy-main">
          <h3 style="color:#fff;margin-bottom:20px;">🔥 本周热门攻略</h3>
          <div class="strategy-item">
            <h4>《黑神话：悟空》全BOSS打法攻略（含精魄推荐）</h4>
            <p>本文汇总了游戏全部BOSS的详细打法，包括属性克制、武器选择、战技搭配。即使是手残玩家也能找到适合自己的通关方案。</p>
            <div class="step">
              <span class="step-num">1</span>
              <span style="color:#888;font-size:0.85em;">了解BOSS攻击规律</span>
            </div>
            <div class="step">
              <span class="step-num">2</span>
              <span style="color:#888;font-size:0.85em;">选择合适的神通和棍法</span>
            </div>
            <div class="step">
              <span class="step-num">3</span>
              <span style="color:#888;font-size:0.85em;">合理利用精魄系统</span>
            </div>
          </div>
          <div class="strategy-item">
            <h4>《艾尔登法环》黄金树幽影 密技位置大全</h4>
            <p>收集所有赐福点附近的隐藏密技，学习失落的古龙职业技能。新版本新增7个密技分布在幽影之地的各个角落。</p>
          </div>
          <div class="strategy-item">
            <h4>《博德之门3》最佳职业组合推荐</h4>
            <p>详细分析各职业特点和协同效果，推荐几套经过验证的强力组合。包含物理队、法术队、双人小队等多种Build方案。</p>
          </div>
        </div>
        <div class="strategy-sidebar">
          <div class="side-card">
            <h4>🏆 攻略热度榜</h4>
            <div class="side-item">
              <span class="side-num">1</span>
              <div class="side-content">
                <h5>黑神话全BOSS打法</h5>
                <p>热度 98.5万</p>
              </div>
            </div>
            <div class="side-item">
              <span class="side-num">2</span>
              <div class="side-content">
                <h5>法环DLC逃课打法</h5>
                <p>热度 76.2万</p>
              </div>
            </div>
            <div class="side-item">
              <span class="side-num">3</span>
              <div class="side-content">
                <h5>博德之门3职业推荐</h5>
                <p>热度 54.8万</p>
              </div>
            </div>
            <div class="side-item">
              <span class="side-num">4</span>
              <div class="side-content">
                <h5>赛博朋克2077流派</h5>
                <p>热度 43.1万</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 游戏工具 -->
    <section id="tools">
      <h2 class="section-title">🔧 游戏工具 <a href="#" class="more">查看更多 &raquo;</a></h2>
      <div class="tools-grid">
        <div class="tool-card">
          <div class="tool-icon">📝</div>
          <div class="tool-info">
            <h4>CE修改器 7.5</h4>
            <p>支持1000+游戏的内存修改工具|更新至最新版</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">📦</div>
          <div class="tool-info">
            <h4>3DM汉化补丁</h4>
            <p>主流3A大作简体中文汉化包|持续更新中</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">🎨</div>
          <div class="tool-info">
            <h4>ReShade画面增强</h4>
            <p>提升游戏画质表现|支持自定义滤镜</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">💾</div>
          <div class="tool-info">
            <h4>云存档管家</h4>
            <p>云端同步存档数据|防止存档丢失</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">⚡</div>
          <div class="tool-info">
            <h4>UU加速器</h4>
            <p>降低游戏延迟丢包|支持主机和PC</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">🖥️</div>
          <div class="tool-info">
            <h4>帧率解锁工具</h4>
            <p>解除游戏帧数上限|支持Vulkan和DX12</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">📋</div>
          <div class="tool-info">
            <h4>Steam跳跳乐</h4>
            <p>解决Steam无法登录|steamcommunity.com访问</p>
          </div>
          <button class="tool-download">下载</button>
        </div>

        <div class="tool-card">
          <div class="tool-icon">🔧</div>
          <div class="tool-info">
            <h4>游戏修复工具</h4>
            <p>修复游戏报错、闪退、缺少DLL等问题</p>
          </div>
          <button class="tool-download">下载</button>
        </div>
      </div>
    </section>

    <!-- 排行榜 -->
    <section id="ranking">
      <h2 class="section-title">🏆 排行榜</h2>
      <div class="ranking-section">
        <div class="ranking-card">
          <h4>🔥 本周热玩榜</h4>
          <div class="ranking-list">
            <div class="ranking-item">
              <span class="rank-num rank-1">1</span>
              <div class="rank-info">
                <h5>黑神话：悟空</h5>
                <p>动作冒险 | 国产之光</p>
              </div>
              <span class="rank-value">152万</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-2">2</span>
              <div class="rank-info">
                <h5>艾尔登法环</h5>
                <p>动作RPG | 经典续作</p>
              </div>
              <span class="rank-value">98万</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-3">3</span>
              <div class="rank-info">
                <h5>霍格沃茨之遗</h5>
                <p>冒险 | 魔法世界</p>
              </div>
              <span class="rank-value">89万</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">4</span>
              <div class="rank-info">
                <h5>博德之门3</h5>
                <p>CRPG | 经典回归</p>
              </div>
              <span class="rank-value">67万</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">5</span>
              <div class="rank-info">
                <h5>使命召唤</h5>
                <p>射击 | 经典IP</p>
              </div>
              <span class="rank-value">54万</span>
            </div>
          </div>
        </div>

        <div class="ranking-card">
          <h4>⭐ 评分排行</h4>
          <div class="ranking-list">
            <div class="ranking-item">
              <span class="rank-num rank-1">1</span>
              <div class="rank-info">
                <h5>黑神话：悟空</h5>
                <p>画面、战斗均为顶级水准</p>
              </div>
              <span class="rank-value">9.8</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-2">2</span>
              <div class="rank-info">
                <h5>艾尔登法环</h5>
                <p>开放世界设计精妙</p>
              </div>
              <span class="rank-value">9.7</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-3">3</span>
              <div class="rank-info">
                <h5>博德之门3</h5>
                <p>剧本质量极高</p>
              </div>
              <span class="rank-value">9.6</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">4</span>
              <div class="rank-info">
                <h5>地平线5</h5>
                <p>画面表现惊艳</p>
              </div>
              <span class="rank-value">9.4</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">5</span>
              <div class="rank-info">
                <h5>战神5</h5>
                <p>战斗系统出色</p>
              </div>
              <span class="rank-value">9.3</span>
            </div>
          </div>
        </div>

        <div class="ranking-card">
          <h4>📈 上升最快</h4>
          <div class="ranking-list">
            <div class="ranking-item">
              <span class="rank-num rank-1">1</span>
              <div class="rank-info">
                <h5>GTA6</h5>
                <p>+38名 | 发售预期升温</p>
              </div>
              <span class="rank-value">↑38</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-2">2</span>
              <div class="rank-info">
                <h5>怪物猎人：荒野</h5>
                <p>+25名 | 测试版上线</p>
              </div>
              <span class="rank-value">↑25</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-3">3</span>
              <div class="rank-info">
                <h5>死亡搁浅2</h5>
                <p>+18名 | 新预告公开</p>
              </div>
              <span class="rank-value">↑18</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">4</span>
              <div class="rank-info">
                <h5>最终幻想7：重生</h5>
                <p>+12名 | PC版预期</p>
              </div>
              <span class="rank-value">↑12</span>
            </div>
            <div class="ranking-item">
              <span class="rank-num rank-other">5</span>
              <div class="rank-info">
                <h5>龙之信条2</h5>
                <p>+8名 | 夏季促销</p>
              </div>
              <span class="rank-value">↑8</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 硬件评测 -->
    <section id="hardware">
      <h2 class="section-title">🖥️ 硬件评测 <a href="#" class="more">查看更多 &raquo;</a></h2>
      <div class="hardware-grid">
        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/PlayStation_5_console_and_controller.png/440px-PlayStation_5_console_and_controller.png" alt="PS5"></div>
          <div class="hardware-info">
            <h4>PlayStation 5 Pro</h4>
            <p>索尼最新游戏主机，搭载升级版GPU，支持8K输出和光线追踪增强。推荐追求极致画质的玩家入手。</p>
            <div class="hardware-price">¥4499 <del>¥4999</del></div>
          </div>
        </div>

        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/Nvidia_logo.svg/440px-Nvidia_logo.svg.png" alt="RTX 5080"></div>
          <div class="hardware-info">
            <h4>RTX 5080 显卡</h4>
            <p>NVIDIA新一代旗舰显卡，Blackwell架构，32GB GDDR7显存，AI算力大幅提升，4K游戏首选。</p>
            <div class="hardware-price">¥8999 <del>¥9999</del></div>
          </div>
        </div>

        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Xbox-Series-X-Console-wController.png/440px-Xbox-Series-X-Console-wController.png" alt="Xbox Series X"></div>
          <div class="hardware-info">
            <h4>Xbox Series X</h4>
            <p>微软最强主机，12 TFLOPS GPU，1TB SSD极速加载。Game Pass订阅超值，畅玩百款大作。</p>
            <div class="hardware-price">¥3599 <del>¥3999</del></div>
          </div>
        </div>

        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Razer_logo.svg/440px-Razer_logo.svg.png" alt="Razer"></div>
          <div class="hardware-info">
            <h4>雷蛇黑寡妇V4 Pro</h4>
            <p>旗舰机械键盘，Gasket结构设计，热插拔轴体，支持2.4GHz无线和蓝牙，RGB灯效炫酷。</p>
            <div class="hardware-price">¥1299 <del>¥1499</del></div>
          </div>
        </div>

        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Logitech_logo.svg/440px-Logitech_logo.svg.png" alt="Logitech"></div>
          <div class="hardware-info">
            <h4>罗技 G PRO X SUPERLIGHT 3</h4>
            <p>顶级无线游戏鼠标，重量仅60g，Hero 25K传感器，续航长达90小时，电竞选手首选。</p>
            <div class="hardware-price">¥899 <del>¥999</del></div>
          </div>
        </div>

        <div class="hardware-card">
          <div class="hardware-img"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Sony_logo.svg/440px-Sony_logo.svg.png" alt="Sony"></div>
          <div class="hardware-info">
            <h4>索尼 WH-1000XM6</h4>
            <p>旗舰降噪耳机，升级版主动降噪，音质出色，佩戴舒适，适合长时间游戏和音乐欣赏。</p>
            <div class="hardware-price">¥2999 <del>¥3499</del></div>
          </div>
        </div>
      </div>
    </section>
  </div>

  <footer>
    <div class="footer-main">
      <div class="footer-about">
        <div class="logo">3DM<span>游戏网</span></div>
        <p>3DM游戏网创建于2009年，是国内知名的游戏综合门户网站。致力于为玩家提供最新最快的游戏资讯、最全最强的游戏攻略、最专业便捷的游戏工具。</p>
      </div>
      <div class="footer-col">
        <h4>游戏分类</h4>
        <a href="#">动作冒险</a>
        <a href="#">角色扮演</a>
        <a href="#">射击游戏</a>
        <a href="#">策略经营</a>
        <a href="#">体育竞技</a>
      </div>
      <div class="footer-col">
        <h4>热门游戏</h4>
        <a href="#">黑神话：悟空</a>
        <a href="#">艾尔登法环</a>
        <a href="#">博德之门3</a>
        <a href="#">赛博朋克2077</a>
        <a href="#">GTA6</a>
      </div>
      <div class="footer-col">
        <h4>关于我们</h4>
        <a href="#">公司简介</a>
        <a href="#">联系方式</a>
        <a href="#">加入我们</a>
        <a href="#">用户协议</a>
        <a href="#">隐私政策</a>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2009-2026 3DM游戏网 All Rights Reserved | <a href="#">京ICP备XXXXXXX号</a></p>
    </div>
  </footer>
</body>
</html>
# 3DM 游戏攻略网

## 1. 项目概述
- **项目名称**: 3DM 游戏攻略网
- **类型**: 游戏资讯攻略网站
- **核心功能**: 游戏新闻、攻略文章、工具下载、玩家社区
- **目标用户**: 游戏玩家

## 2. 页面结构
- 顶部导航（游戏分类）
- 首屏Banner
- 热门游戏推荐
- 最新攻略文章
- 游戏工具下载区
- 底部信息

## 3. 设计风格
- 深色主题，游戏风格
- 红色橙色强调色（3DM标志色）
- 卡片式布局
Add-Type -AssemblyName System.Net.Http
$client = New-Object System.Net.Http.HttpClient
$content = New-Object System.Net.Http.ByteArrayContent([System.IO.File]::ReadAllBytes("C:\Users\Lenovo\3dm-guide\index.html"))
$form = New-Object System.Net.Http.MultipartFormDataContent
$form.Add($content, "file", "index.html")
$response = $client.PostAsync("https://catbox.moe/user/api.php", $form).Result
Write-Output $response.Content.ReadAsStringAsync().Result
<!DOCTYPE html>
<html>
<head>
  <title>3DM游戏攻略</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gist-embed@1.0.4/dist/gist-embed.min.css">
  <style>
    body { margin: 0; padding: 20px; background: #121212; }
  </style>
</head>
<body>
  <div id="gist-123456">Loading...</div>
  <script src="https://cdn.jsdelivr.net/npm/gist-embed@1.0.4/dist/gist-embed.min.js"></script>
  <script>
    gistEmbed.embed('https://gist.github.com/a1833636251-dev/bca2c4fa12cde267d0f3ce0376fe4b9d', document.getElementById('gist-123456'));
  </script>
</body>
</html>
$token = "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"
$filePath = "C:\Users\Lenovo\3dm-guide\index.html"
$content = Get-Content $filePath -Raw

$body = @{
    description = "3DM游戏攻略网页"
    public = $false
    files = @{
        "index.html" = @{ content = $content }
    }
}

$json = $body | ConvertTo-Json -Depth 10
$headers = @{
    "Authorization" = "Bearer $token"
    "User-Agent" = "Mozilla/5.0"
    "Content-Type" = "application/json"
}

try {
    $response = Invoke-WebRequest -Uri "https://api.github.com/gists" -Method Post -Headers $headers -Body ([System.Text.Encoding]::UTF8.GetBytes($json)) -ContentType "application/json" -TimeoutSec 60
    $result = $response.Content | ConvertFrom-Json
    Write-Output "SUCCESS"
    Write-Output "Gist URL: $($result.html_url)"
} catch {
    Write-Output "ERROR: $_"
    Write-Output $_.Exception.Message
}
