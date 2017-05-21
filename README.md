# NotePad
This is an AndroidStudio rebuild of google SDK sample NotePad
# 1、首先是时间显示问题
#### 我们先从view开始，先把要显示时间的view做好。经过观察，本程序在NotesList中继承ListActivity来显示笔记列表，NotesList中使用了SimpleCursorAdapter来绑定数据，我们可以看到每个Item的view是用R.layout.noteslist_item，所以我们在res中找到layout->noteslist_item这个xml，在原本显示标题的TextView下增加一个显示时间的TextView。

