# GRE Daily (Chinese Version / 中文版)

A single-page GRE vocabulary review site designed for GitHub Pages.  
一个为 GitHub Pages 设计的单页 GRE 背单词网站。

## Features / 功能

- Daily new-word quota is configurable.  
  可自由设置每天学习的新单词数量。

- Changing the quota takes effect immediately and remains the default for future days.  
  修改每日新词数量后会立即生效，并作为之后每天的默认学习数量。

- Shows an estimate of how many days remain to finish the first pass of new words.  
  自动估算按照当前每日新词数量，还需要多少天完成第一轮全部新词学习。

- Review scheduling is handled automatically in the browser.  
  复习计划由浏览器自动安排，无需手动设置复习时间。

- "Known" is on the left; "Unknown" is on the right.  
  “认识”按钮在左侧，“不认识”按钮在右侧。

- Unknown words are reinserted later in the same day's queue.  
  点击“不认识”的单词会在当天稍后的学习队列中重新出现。

- Words can be moved directly to the trash without a confirmation dialog.  
  已经完全掌握的单词可以直接放入垃圾桶，不会弹出二次确认。

- Progress is stored locally in the browser with `localStorage`.  
  学习进度通过浏览器的 `localStorage` 保存在本地。

- No backend/database is required.  
  不需要后端服务器或数据库。

## Notes / 注意事项

- The first successful load requires internet access to fetch the vocabulary data.  
  第一次成功打开网站时需要联网，用于获取完整词库数据。

- After that, the vocabulary cache and learning progress are stored in that browser.  
  成功加载后，词库缓存和学习进度都会保存在当前浏览器中。

- Progress does not automatically sync across different devices or browsers.  
  不同设备或不同浏览器之间不会自动同步学习进度。

- Clearing site data/local storage will erase the local learning progress.  
  如果清除浏览器网站数据或 `localStorage`，本地学习进度也会被删除。
