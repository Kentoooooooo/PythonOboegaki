## format構文の利用方法
文字列.format(この中でそれぞれの中身を指定する)

##利用例

card = """\
株式会社ビープラウド
{job_title}
{name}
MAIL: {mail}
TEL: 03-9999-9999 FAX: 03-9999-9998 内線: {extension}
URL: https://www.beproud.jp
"""

# この下に処理を記述します
sato_card = card.format(job_title='エンジニア', 
                        name='佐藤太郎', 
                        mail='taro@beproud.jp', 
                        extension='1234')

print(sato_card)
