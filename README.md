# ffmq-score-calcuation-gas (EN)
Calculates FFMQ scores from Google Form input using GAS. It also provides 5 facet scores as well as total scores.

## Google Form Requirements
Google Form should:
- start from a question for participant id: e.g. p1, p2, ...
- be followed by FFMQ questions of 39 items.
- should NOT have any other unecessary question items.


5-choise are written in Japanese. If you want to use English, you need to modify the array `expectedStrScores`.

```
['まったくあてはまらない', 'めったにあてはまらない', 'たまにあてはまる', 'しばしばあてはまる', 'いつもあてはまる']
```

Score corresponding to each item in the list above is 1, 2, 3, 4, and 5 respectively.

# References

## FFMQ - Japanese version (with backtranslation)
Sugiura, Y., Sato, A., Ito, Y., Murakami, H. (2012). Development and validation of the Japanese version of the Five Facet Mindfulness Questionnaire, Mindfulness, 3, 85-94.
https://doi.org/10.1007/s12671-011-0082-1

## FFMQ - Original version
Baer, R. A., Smith, G. T., Hopkins, J., Krietemeyer, J., Toney, L. (2006). Using self-report assessment methods to explore facets of mindfulness. Assessment, 13, 27-45.

# DISCLAIMER

I have exhasutively checked score calculations, but if you find mistakes, please let me know.
Please note that I do not take any responsibility or liability for any damage or loss caused by my script.
However, it would be great if my script can help other researchers who suffer from manual calculations of ffmq scores.

**Kanta Yamaoka**
myfirstname.mylastname(at-mark)m.cs.osakafu-u.ac.jp
https://jp.linkedin.com/in/kanta-yamaoka


# ffmq-score-calcuation-gas (JA)
このリポジトリのGASのコードを利用することでFFMWスコアをGoogle Formを通して計算することができます。トータルスコアだけでなく、５つの側面のスコアも計算できます。

## Google Formの満たすべき要件
Google Formは以下を満たすようにしてください:
- 最初の質問は実験参加者のID等（例：p1, p2, ...）
- その後の質問はFFMQの39問が続く
- これ以外の不必要な質問項目はない


# 参考

## FFMQ - Japanese version (with backtranslation)
Sugiura, Y., Sato, A., Ito, Y., Murakami, H. (2012). Development and validation of the Japanese version of the Five Facet Mindfulness Questionnaire, Mindfulness, 3, 85-94.
https://doi.org/10.1007/s12671-011-0082-1

## FFMQ - Original version
Baer, R. A., Smith, G. T., Hopkins, J., Krietemeyer, J., Toney, L. (2006). Using self-report assessment methods to explore facets of mindfulness. Assessment, 13, 27-45.

# 免責

コード中のスコアの計算の検算は行っていますが、もし間違いがありましたら教えてください。
このスクリプトを利用したことによる損害や損失などに対して私は責任は負えないことをご理解ください。
とはいうものの、このスクリプトが他の研究者の方々の面倒な手計算や、エクセル計算から逃れる助けになれば、この上ない幸せです。

専門は情報工学ですが、心理学などの学際的な研究を行っています。とくに、マインドフルネスに大きな関心があります。
似たような興味をお持ちのかたは、ぜひご連絡ください！一緒に研究しましょう！

**Kanta Yamaoka 山岡幹太**
myfirstname.mylastname(at-mark)m.cs.osakafu-u.ac.jp
https://jp.linkedin.com/in/kanta-yamaoka
