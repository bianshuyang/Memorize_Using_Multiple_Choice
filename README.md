# Memorize_Using_Multiple_Choice
Generate an html file that is also available for running on mobile device. This file allows modification so that as long as you have a pair of matched words/terminology, you could recite them in a multiple choice model.
# 项目起源
很多时候背单词软件要求用户选择“认识”或者“不认识”。不幸的是，对我这类学习者而言，“认识”和“不认识”的边界非常模糊，而且也非常取决于用户的主观能动性。而选择题作为客观的测试形式，能够增加迷惑选项，有效杜绝用户自我欺骗，从而达到成功背诵的目的。
# 项目用法
这是一个html文件，只需要修改1.js即可。这个js文件可以使用txt打开，把所有的题目用这样的形式编写：words = ['题目1','题目2','...']。必须要注意：开头是[，结尾也是]，最后所有的撇和逗号必须是半角。
而把所有的答案按照这样的形式编写：ans = ['答案1','答案2']
# 如果你的题目数量比较大
则可以在第（框框）个List里面输入数字。一组list是100个词，每背完100个词，就会在下方第X遍背诵处增加1遍，一般来说，背上5遍也就很容易记住了。
# 错题
错题会在单击错误答案后自动跳出。
**** 用一个js文件作为一个列表，然后包括所有的试题和答案这件事情做得挺蠢的，因为html纯自学，我还是很想了解不通过这么愚笨的办法把这么多数据加载的办法的。提前谢谢。
