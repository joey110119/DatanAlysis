# Data analysis

part2 的說明解釋，都有 print 在 .ipynb 輸出的圖案旁邊方便查閱，以下為中文的詳細解釋。

Data 取自 ： https://www.kaggle.com/abcsds/pokemon

part2 使用一份 Pokemon 的 data，主要探討了四個主題

一，因為每個世代的 Pokemon 作者都會加入新的 Pokemon，所以透過表格輸出查看每個世代誰的 Pokemon 數目最多

二，每隻 Pokemon 都有所屬的屬性(type)，而且可能不只一種屬性(最高兩種)，因此我在該主題透過表格計算出每個不同屬性的 Pokemon 數目，以及透過文字輸出哪種屬性的 Pokemon 是最多的

三，每隻 Pokemon 都有不同的速度，攻擊，防禦，特攻，特防，血量。因此在這個主題中我透過 heatMap 去探討了不同屬性之間的相關性。而就結果看來最為明顯的是'最低'這個特徵，最低的是防禦和速度這兩個屬性，可以想像的是防禦往往都是較為笨重的 Pokemon 所以速度相對的也較慢，是非常合理的

四，Pokemon 中有三個屬性是最能讓人聯想到速度的，飛行系，蟲系，龍系，因此我透過加總所有這三個屬性 Pokemon 的 Speed 數值，再去個別除以這三個屬性的數目，畫出樹狀圖來做比較
