(See below for the English version.)

課題 #1
会社が社員に支給する給与額を計算するの代表的な数値である、月あたりの

法定内残業時間数
法定外残業時間数
深夜残業時間数
所定休日労働時間数
法定休日労働時間数
を計算するプログラムを作ってください。

今回の算出対象となる社員は、

休日は土曜日および日曜日とする
法定休日は毎週日曜日とする
1 週間は月曜日から日曜日までとする
勤務時間を 8:00〜16:00 とする
12:00〜13:00 を所定の休憩時間とする
の勤務形態であるとします。

また、

実労働時間が 1 日あたり 8 時間を超える、もしくは 1 週間あたり 40 時間を超える場合は、 25% 増の賃金を支払う
22:00 〜 翌5:00 の間の労働には、25% 増の賃金を払う
所定休日の間の労働には、25% の割増賃金を払う
法定休日の間の労働には、35% の割増賃金を払う
ただし、所定休日および法定休日の労働には時間外労働の割増率を適用しない

時間外労働時間を計算する場合は、1 日の起点を 5:00 とする

所定休日・法定休日における労働時間を計算する場合は、1 日の起点を 0:00 とする
ものとします。

また、時間数の計算にあたっては、

日々の集計は分単位で行う
月あたりの集計値として 1 時間未満の端数処理を行う場合は、 30 分未満を切り捨て、30 分以上を切り上げるものとする
こととします。

単語解説
法定内残業

会社の就業規則で定めている労働時間 (所定労働時間) が、 労働基準法で定められている「1 日 8 時間」「1 週 40 時間」(法定労働時間) を下回っている場合、 「所定労働時間は超えているが法定労働時間は超えない時間の残業」を指して「法定内残業」といいます。

労働基準法では、法定内残業には所定労働に対する賃金 (所定賃金) を支払えばよいことになっています。

法定外残業

法定労働時間を超える残業のことを「法定外残業」と言います。 残業に限らないという意味で、「時間外労働」とも言います。

法律上、法定外残業を行うには、いわゆる「36 (さぶろく) 協定」という労使協定を結ぶ必要があります。

法定外残業には所定賃金を一定割合 (労働基準法では 25% 以上と定められています で乗じた割増賃金を支払わなければなりません。

深夜残業

22:00 〜 翌5:00 の間の労働を「深夜残業」と言います。 深夜残業には所定賃金を一定割合 (労働基準法では 25% 以上と定められています で乗じた割増賃金を支払わなければなりません。

法定外残業と深夜残業とが重なった場合は、それぞれの割増賃金を合わせた額 (50%) を支払わなければなりません。

法定休日

労働基準法では、使用者は毎週少なくとも 1 回の休日、 もしくは 4 週間を通じて 4 日の休日を与えなければならないと定められています。 労働基準法で定められている休日のことを法定休日と言います。

法律上、法定休日における労働には所定賃金を一定割合 (労働基準法では 35% 以上と定められています で乗じた割増賃金を支払わなければなりません。

法定休日における労働時間は、時間外労働のカウント外になります。 そのため、「1 日 8 時間」「1 週 40 時間」を超えた労働に 法定外残業の割増賃金を支払う必要はありません。

所定休日

勤務時間を 1 日あたり 7 〜 8 時間としている会社の場合、 1 週間に 1 度の休日では、週の労働時間が 40 時間を超えてしまいます。 そのため、基本的には週にもう 1 日の休日を設けることになります。

この他に、国民の祝日などを休日とする場合も、所定休日となります。

法律上、法定休日を特定の曜日にする必要はありません。 法定休日が定められていない場合、 一般的には「1 週間のうちで最後の休日」を法定休日と解釈されることが多いです。

1 日、1 週間

「1 週間」は、会社の就業規則等で特に定められていない場合は、 歴週 (日曜日から土曜日まで) となります。 また、「1 日」とは原則として暦日 (0:00〜24:00) を指します。 ただし、継続勤務が日付を超えて 2 暦日にわたる場合、 それを 1 勤務として取り扱い、その勤務は始業時刻の属する日の労働として取り扱われます。

休憩時間

労働基準法では、労働時間が 6 時間を超える場合には少なくとも 45 分、 8 時間を超える場合は少なくとも 1 時間の休憩時間を与えなければなりません。

賃金の端数処理

労働基準法では、賃金は全額支払わなければなりません。 したがって、原則として労働者にとって不利になる労働時間や賃金の端数処理 (切り捨て) はできません。 そのため、会社は正確に労働時間を記録し、その記録に基づいて賃金を支給する必要があります。

ただし、通達によりいくつかのケースにおいて、 四捨五入のような (労働者にとって不利になる可能性のある) 端数処理を行う例外が認められています。

時間数の計算例
この会社における具体的な計算例は以下の通りです。

Case 1: 所定時間通りに勤務した場合
実労働時間: 8:00〜12:00、13:00〜16:00
この場合、実労働時間 7 時間はすべて所定勤務時間となります。

※ それ以外の時間数にはカウントされません

法定内残業時間数	0
法定外残業時間数	0
深夜残業時間数	0
所定休日労働時間数	0
法定休日労働時間数	0
Case 2: 法定内残業がある場合
実労働時間が所定労働時間数を超過し、かつ 8 時間を超過しない時間を 「法定内残業時間」とします。

実労働時間: 8:00〜12:00、13:00〜17:00
実労働時間は 8 時間なので、 所定労働時間を超える 16:00 〜 17:00 の間は法定内残業時間になります。

法定内残業時間数	1
法定外残業時間数	0
深夜残業時間数	0
所定休日労働時間数	0
法定休日労働時間数	0
Case 3: 法定外残業がある場合
実労働時間が 8 時間を超過した場合は、その超過した時間を「法定外残業時間」とします。

実労働時間: 8:00〜12:00、13:00〜21:00
実労働時間 12 時間のうち、 所定労働時間を超える 16:00 〜 17:00 の間は法定内残業時間、 8 時間を超える 17:00 〜 21:00 の間は所定外残業時間になります。

法定内残業時間数	1
法定外残業時間数	4
深夜残業時間数	0
所定休日労働時間数	0
法定休日労働時間数	0
Case 4: 不就労働時間の扱いについて
遅刻・早退などの不就労働があった場合には、その時間数を実労働時間から減算し、残業時間を算出します。

実労働時間: 10:00〜12:00、13:00〜21:00
この場合、2 時間 (8:00 〜 10:00) の不就労働があるため、16:00 までの実労働時間が 5 時間とします。 そのため、法定内残業時間 (実労働時間が8時間に満たない勤務時間数) が 16:00～19:00 までの3時間、 法定外残業時間 (実労働時間が8時間を超過する勤務時間数) が 19:00～21:00 の 2 時間と計算します。

法定内残業時間数	3
法定外残業時間数	2
深夜残業時間数	0
所定休日労働時間数	0
法定休日労働時間数	0
Case 5: 深夜残業がある場合
勤務を行う時間帯が、22:00 ～ 翌 5:00 の間の時間帯の場合には、 その間の労働時間を「深夜労働時間」とします。

実労働時間: 8:00〜12:00、13:00〜26:00
この場合、法定外残業時間 17:00〜26:00 (9 時間) のうち、 22:00〜26:00 の 4 時間を深夜残業時間数とします。

なお、22:00〜26:00 の 4 時間については、 法定外残業の割増賃金 (25%) と深夜残業の割増賃金 (25%) を合わせた割増賃金 (50%) が支給されることになります。

法定内残業時間数	1
法定外残業時間数	9
深夜残業時間数	4
所定休日労働時間数	0
法定休日労働時間数	0
Case 6: 所定休日に労働する場合
所定休日に労働する場合は、そのすべてを所定休日労働時間数とします。

実労働時間: 8:00〜12:00、13:00〜23:00 (土曜日)
実労働時間 14 時間はすべて所定休日労働時間数となります。 また、22:00〜23:00 は深夜残業時間となります。

法定内残業時間数	0
法定外残業時間数	0
深夜残業時間数	1
所定休日労働時間数	14
法定休日労働時間数	0
Case 7: 日跨ぎ残業が所定休日にかぶる場合
実労働時間: 8:00〜12:00、13:00〜26:00 (金曜日)
24:00〜26:00 の勤務は所定休日労働になります。 残りの 8:00〜12:00、13:00〜24:00 の勤務に対して、 法定内残業時間数、法定外残業時間数を計算します。

また、22:00〜26:00 の勤務は深夜残業となります。

法定内残業時間数	1
法定外残業時間数	7
深夜残業時間数	4
所定休日労働時間数	2
法定休日労働時間数	0
Case 8: 法定休日に労働する場合
所定休日と同様に計算します。

実労働時間: 8:00〜12:00、13:00〜23:00 (日曜日)
法定内残業時間数	0
法定外残業時間数	0
深夜残業時間数	1
所定休日労働時間数	0
法定休日労働時間数	14
Case 9: 所定休日から法定休日に日を跨いで労働する場合
実労働時間: 8:00〜12:00、13:00〜26:00 (土曜日)
24:00 を境に所定休日労働時間から法定休日労働時間に切り替わります。

法定内残業時間数	0
法定外残業時間数	0
深夜残業時間数	4
所定休日労働時間数	15
法定休日労働時間数	2
Case 10: 1 週間の労働時間が 40 時間を超える場合
実労働時間: 8:00〜12:00、13:00〜21:00
前日までに 35 時間の労働を行っている
1 週間の労働が 40 時間を超えない 8:00〜12:00 および 13:00〜14:00 を所定内労働時間 (5 時間) とし、残りの 14:00〜21:00 (7 時間) のすべてを法定外残業時間数とします。

法定内残業時間数	0
法定外残業時間数	7
深夜残業時間数	0
所定休日労働時間数	0
法定休日労働時間数	0
課題の仕様
プログラムの実行方法
※ $ はプロンプト文字列を表します。

プログラムは以下のコマンドでビルドされるものとします。 いくつかのプログラミング言語の標準的なビルド構成が ./build.sh に定義されています。 不要な言語の記述を削除し、適切にビルドされるようにしてください。

  $ ./build.sh
このコマンドはテスト実行に先立って 1 度だけ実行されます。

プログラムは以下のコマンドで実行されるものとします。 いくつかのプログラミング言語の標準的な実行構成が ./run.sh に定義されています。 不要な言語の記述を削除し、適切に実行されるようにしてください。

  $ ./run.sh
このコマンドはテスト実行時に何度か実行されます。

入力データの形式
入力は、月を跨ぐ最初の週の月曜日から、月末日までが以下の形式で標準入力に渡されます。

1行目は集計対象月が YYYY/MM の形式
2行目以降は労働時間が日付順に YYYY/MM/DD HH24:mm-HH24:mm HH24:mm-HH24:mm ... の形式で渡される
1列目は対象日付を、2列目以降は休憩時間を含まない実労働時間を表す
日付を跨ぐ勤務は、14:00-25:00 のように 24 時を超える形式で渡される
労働開始時刻は 05:00 以後であること、労働終了時刻は 29:00 までであることを前提にして良い
すなわち、深夜労働時間は 22:00 から 29:00 の時間帯に限られる
労働時間が発生しない日 (休日や欠勤日) の労働時間は渡されない
例:

2017/02
2017/01/30 08:00-12:00 13:00-16:00
2017/01/31 08:00-12:00 13:00-16:00
2017/02/01 08:00-12:00 13:00-16:00
2017/02/02 08:00-12:00 13:00-16:00
2017/02/03 08:00-12:00 13:00-16:00
2017/02/06 13:00-16:00
2017/02/07 08:00-12:00 13:00-16:00 17:00-23:00
      (途中省略)
2017/02/28 08:00-12:00 13:00-16:00
この例では、集計対象は 2017/02/01〜2017/02/28 までですが、 2月1日が水曜日なので、その週に含まれる 1月30日および31日の行が入力として渡されます。

出力データの形式
法定内残業時間数(時)
法定外残業時間数(時)
深夜残業時間数(時)
所定休日労働時間数(時)
法定休日労働時間数(時)
をこの順に標準出力に1行ずつ出力します。

これらの時間数は、日々の計算においては「分単位」で計算し、 1ヶ月分の累計の算出時に、1時間に満たない端数を、30分未満を切り捨て、30分以上を切り上げで丸め処理するものとします。

例:

15
20
5
4
5
この例では、法定内残業時間数: 15時間、法定外残業時間数: 20時間、 深夜残業時間数: 5時間、所定休日労働時間数: 4時間、法定休日労働時間数: 5時間を表します。

プログラムは、適切な入力データが渡される限りにおいては、終了コードとして 0 を返すものとします。 また、上記以外の出力を標準出力に行ってはいけません。 標準エラー出力には任意の出力を行っても構いません (無視されます)。

プログラムは、不適切な入力データが渡された場合は、0 以外の終了コードを返すものとします。 この時、標準出力には一切の出力を行ってはいけません。 標準エラー出力には任意の出力を行っても構いません (無視されます)。

プログラムのテスト方法
プログラムのテストは、bash 上の codecheck コマンドで実行できます。

$ codecheck
codecheck コマンドの実行には、NodeJS が必要となります。

codecheck コマンドは npm でインストールできます。 また、テストフレームワークとして mocha を使っているため、 mocha のインストールも必要になります。

$ npm install -g codecheck
$ npm install -g mocha
codecheck コマンドは、./test.sh の内容を実行しているだけなので、 Windows 等 bash の無い環境では、./test.sh の内容を手動で実行しても構いません。

例えば、Java の場合は次のようになります。

> cd java
> mvn package -Dmaven.test.skip=true
> cd ..\test
> npm install
> cd ..
> mocha test\test*.js
test ディレクトリには基本的なテストケースが用意されています。 この他、任意のテストケースを追加 (test/test_optional.js) しても構いません。

(English Version)

Examination
The following are the major values used to calculate the salary paid to company’s employees. Please create a program for computing amount of salary per month.

Overtime within statutory working hours
Overtime in excess of statutory working hours
Late-night overtime working hours
Working hours on prescribed holiday
Working hours on Statutory holiday
Target employees of the calculation are working under the following conditions:

Holidays are Saturdays and Sundays.
Statutory holidays are every Sunday.
A week starts on Monday ending on Sunday.
Regular daily working hours are 8:00～16:00.
Prescribed break time is 12:00～13:00.
In addition, they are subject to the following conditions:

Employees will get paid 25% increase of wages when working in excess of 8 hours, or in excess of 40 hours per week.
Employees will get paid 25% increase of wages for working between 22:00 and 5:00 the following day.
Employees will get paid 25% increase of wages for working during prescribed holiday.
Employees will get paid 35% increase of wages for working during statutory holiday.
However, the increased rate of wages for overtime work will not be applied to works on prescribed holiday and statutory holiday.
For calculating overtime working hours, the start of a day is defined as 5:00.
For calculating working hours of prescribed holiday/ statutory holiday, the start of a day is defined as 0:00.
The following rules will be applied when computing the number of hours:

Daily aggregation is done in the unit of minutes.
To tally monthly hours, round off/up amount less than one hour based on the following; round off if less than 30 minutes, round up if 30 minutes or more.
Term Commentary
Overtime within statutory working hours
“Overtime which time length exceeds the prescribed working hours but does not exceed statutory working hours” is defined as “Overtime within statutory working hours” for a case where the working hours (prescribed working hours) set by the company’s work regulations are below “8 hours per day” or “40 hours per week” (statutory working hours). Employers are required by the law to pay for overtime within statutory working hours the wages against prescribed work (prescribed wages).

Overtime in excess of statutory working hours
Overtime work that exceeds statutory working hours is defined as “Overtime in excess of statutory working hours”. It can also be expressed as “overtime work”. The law stipulates that to have employees work in excess of statutory working hours, employers are required to conclude so called the Article 36 agreement which is a labor-management agreement. For the overtime in excess of statutory working hours, companies must pay wages of an increased rate (25% or more), 1.25 times the prescribed wages.

Late-night overtime
Works during the time period between 22:00 and 5:00 the following day, is defined as “late-night overtime”. Wages of an increased rate (25% or more), 1.25 times the prescribed wages, must be paid. If the overtime in excess of statutory working hours overlaps with the late-night overtime, companies must pay the sum of each extra wages (50% or more).

Statutory holiday
The law stipulates that employers must grant at least one off day per week, or four days of off in any four-week period. The day off specified in the law is defined as statutory holiday. For the work on statutory holiday, wages of a certain increased rate (35% or more), multiplied against the prescribed wages, must be paid according to the law. The working hours on statutory holiday are excluded from the overtime work count. Therefore, in this case, employers do not require to pay increased rate of the wages paid for overtime in excess of statutory working hours against the works exceeding “8 hours per day” or “40 hours per week”.

Prescribed holiday
If a company sets its working hours to 7-8 hours per day, the weekly working hours will exceed 40 hours with only one day off per week. Therefore another day off per week is set, in principle, which is defined as prescribed holiday. If national holidays are set as day offs, they also will be defined as prescribed holiday. The law does not require to set a certain day of week to prescribed holiday. In a case statutory holiday is not defined, in general, “the last one of holidays in a week” is interpreted as statutory holiday.

1 day, 1 week
When “one week” is not specifically defined in company’s work regulations, it will be defined as calendar week (Sunday through Saturday). And “one day”, in principle, indicates a calendar day (00:00-24:00). However, if continued working hours crosses days, spanning two calendar days, it will be handled as one workday of the date to which the workday start time belongs.

Break time
The law stipulates that when the working hours exceed 6 hours, at least 45 minute break, if exceeding 8 hours, one hour break must be given.

Rounding figures of wages
According to the law, employers are obliged to pay the full amount of wages to their workers. Therefore, in principle, it is not allowed to round figures (round off) of working hours or wages against the interest of workers. As it is, companies are required to record accurately the working hours of their employees, and to pay wages based on the records. However, in some cases, it is allowed under exceptional circumstances to round figures that could be against workers’ interest.

Samples of computing number of hours
The following are the specific cases how this company calculates the figures:

Case 1: Worked for exactly the prescribed working hours
Actual working hours: 8:00-12:00, 13:00-16:00
In this case, 7 hours of actual working hours are all counted as prescribed working hours.

※ They will not be counted in other categories of hours.

Overtime within statutory working hours	0
Overtime in excess of statutory working hours	0
Late-night overtime working hours	0
Working hours on prescribed holiday	0
Working hours on Statutory holiday数	0
Case 2: Worked overtime within statutory working hours
When the actual working hours exceed prescribed working hours, but do not exceed 8 hours, the overtime portion is handled as “overtime within statutory working hours”.

Actual working hours: 8:00-12:00, 13:00-17:00
The actual working hours are 8 hours, so the working hours of 16:00-17:00 that exceed prescribed working hours are counted as the overtime within statutory working hours.

Overtime within statutory working hours	1
Overtime in excess of statutory working hours	0
Late-night overtime working hours数	0
Working hours on prescribed holiday	0
Working hours on Statutory holiday	0
Case 3: Worked Overtime in excess of statutory working hours
When the actual working hours exceed 8 hours, the exceeding hours are handled as “Overtime in excess of statutory working hours”.

Actual working hours: 8:00-12:00, 13:00-21:00
Of the actual 12 working hours, the portion exceeding the prescribed working hours, 16:00-17:00, are counted as overtime within statutory working hours, and the portion that exceeds 8 hours, 17:00-21:00 are handled as Overtime in excess of statutory working hours.

Overtime within statutory working hours	1
Overtime in excess of statutory working hours	4
Late-night overtime working hours	0
Working hours on prescribed holiday	0
Working hours on Statutory holiday	0
Case 4: Handling of no-work hours
If there is no-work period such as arriving late or early leaving, the amount of hours will be deducted from the actual working hours and the overtime hours will be calculated.

Actual working hours: 10:00-12:00, 13:00-21:00
In this case, as there are 2 hours (8:00-10:00) of no-work, the actual working hours until 16:00 are 5 hours. Therefore, the overtime within statutory working hours (actual working hours of less than 8 hours) is applied to 3 hours of 16:00-19:00, while overtime in excess of statutory working hours (actual working hours exceeding 8 hours) is applied to 2 hours of 19:00-21:00.

Overtime within statutory working hours	3
Overtime in excess of statutory working hours	2
Late-night overtime working hours	0
Working hours on prescribed holiday	0
Working hours on Statutory holiday	0
Case 5: Worked late-night overtime
Working time window between 22:00 and 5:00 the following day is handled as “late-night working hours”.

Actual working hours: 8:00-12:00, 13:00-26:00
In this case, of the 9hr-overtime in excess of statutory working hours, 4 hours in 22:00-26:00 are handled as late-night overtime hours. Note that the 4 hours in 22:00-26:00 are subject to the wages of combined increased rates (50%), rates for overtime in excess of statutory working hours (25%) and late-night overtime (25%) put together.

Overtime within statutory working hours	1
Overtime in excess of statutory working hours	9
Late-night overtime working hours	4
Working hours on prescribed holiday	0
Working hours on Statutory holiday	0
Case 6: Worked on prescribed holiday
All the working hours on prescribed holiday are handled as working hours on prescribed holiday.

Actual working hours: 8:00-12:00, 13:00-23:00 (Saturday)
The actual working hours of 14 hours are all handled as working hours on prescribed holiday. And the hours in 22:00-23:00 are late-night overtime working hours.

Overtime within statutory working hours	0
Overtime in excess of statutory working hours	0
Late-night overtime working hours	1
Working hours on prescribed holiday	14
Working hours on Statutory holiday	0
Case 7: Overtime crossing days falling on prescribed holiday
Actual working hours: 8:00-12:00, 13:00-26:00 (Friday)
The working hours in 24:00-26:00 are counted as work on prescribed holiday. Overtime within statutory working hours and overtime in excess of statutory working hours are computed against the works in remaining hours: 8:00-12:00, 13:00-24:00. And the working hours in 22:00-26:00 are counted as late-night overtime.

Overtime within statutory working hours	1
Overtime in excess of statutory working hours	7
Late-night overtime working hours	4
Working hours on prescribed holiday	2
Working hours on Statutory holiday	0
Case 8: Worked on statutory holiday
The same calculation as that for prescribed holiday will be applied.

Actual working hours: 8:00-12:00, 13:00-23:00 (Sunday)
Overtime within statutory working hours	0
Overtime in excess of statutory working hours	0
Late-night overtime working hours	1
Working hours on prescribed holiday	0
Working hours on Statutory holiday	14
Case 9: Worked crossing days, from prescribed to statutory holiday
Actual working hours: 8:00-12:00, 13:00-26:00 (Saturday)
When crossing 24:00, the day switches from prescribed holiday to statutory holiday.

Overtime within statutory working hours	0
Overtime in excess of statutory working hours	0
Late-night overtime working hours数	4
Working hours on prescribed holiday	15
Working hours on Statutory holiday	2
Case 10: Working hours in one week exceeded 40 hours
Actual working hours: 8:00-12:00, 13:00-21:00
The total of working hours up to the previous day is 35 hours.
The working hours of 8:00-12:00 and 13:00-14:00 that do not exceed 40 hours are counted as working hours within prescribed working hours (5 hours). The rest, 14:00-21:00 (7 hours), are all counted as overtime in excess of statutory working hours.

Overtime within statutory working hours	0
Overtime in excess of statutory working hours	7
Late-night overtime working hours	0
Working hours on prescribed holiday	0
Working hours on Statutory holiday	0
Specifications of this probelm
How to execute the program
※ $ means prompt character.

The program shall be built with the following command. A standard build configuration for several programming languages is defined in ./build.sh. Delete the description of unnecessary language and make it properly built.

```bash
$ ./build.sh
```

This command is executed only once before the test run.
The program is executed with the following command. A standard build configuration for several programming languages is defined in ./build.sh. Delete the description of unnecessary language and make it properly built.

  $ ./run.sh
This command will be executed several times during test run.

Format of input data
Input the data from Monday of the first week that crosses months to the month end in the following format.

1st line: Month target of aggregation→YYYY/MM
2nd line onward: Working hours→YYYY/MM/DD HH24:mm-HH24:mm HH24:mm-HH24:mm (in date order)
1st line: Target date
2nd line onward: Actual working hours excluding break time
Working hours crossing days are denoted in figures exceeding 24 hours. ex) 14:00-25:00
Precondition: Work start time is 05:00 or later, end time is 29:00 or earlier
i.e: Late-night working hours are limited to the time window of 22:00-29:00
Not possible to enter working hours of days during which working hours do not generate (holiday and day off)
Example:

2017/02
2017/01/30 08:00-12:00 13:00-16:00
2017/01/31 08:00-12:00 13:00-16:00
2017/02/01 08:00-12:00 13:00-16:00
2017/02/02 08:00-12:00 13:00-16:00
2017/02/03 08:00-12:00 13:00-16:00
2017/02/06 13:00-16:00
2017/02/07 08:00-12:00 13:00-16:00 17:00-23:00
....
2017/02/28 08:00-12:00 13:00-16:00
In this case, the target period of aggregation is 2017/02/01 ? 2017/02/28. As February 1st falls on Wednesday, the lines of January 30th and 31st in the same week will be included in the entry.

Format of output data
Output line by line to the standard output in the order shown below;

Overtime within statutory working hours (hrs)
Overtime in excess of statutory working hours (hrs)
Late-night overtime working hours (hrs)
Working hours on prescribed holiday (hrs)
Working hours on statutory holiday (hrs)
Please calculate these hours in minutes in daily calculations. When calculating the cumulative amount for one month, if fractions less than one hour occurred, truncate if less than 30 minutes, round up if 30 minutes or more.

:

15
20
5
4
5
In this case, '15' means "Overtime within statutory working hours:15 hours", '20' means "Overtime in excess of statutory working hours:20 hours", '5' means "Late-night overtime working hours:5 hours", '4' means "Working hours on prescribed holiday:4 hours", and '5' means "Working hours on Statutory holiday:5 hours".

If appropriate input data is passed, the program returns 0 as the exit code. Also, do not output other than the above to standard output. Any output can be output to the standard error output (it is ignored).

If incorrect input data is passed, the program returns a non-zero exit code. At this time, do not output any output to the standard output. Any output can be output to the standard error output (it is ignored).

How to test the program
You can test the program with the codecheck command on bash.

$ codecheck
To execute the codecheck command, NodeJS is required.

Codecheck command can be installed via npm. Since mocha is used as a test framework, mocha installation is also required.

$ npm install -g codecheck
$ npm install -g mocha
codecheck command is only executing the contents of./test.sh. In an environment without bash such as Windows, you can manually execute the contents of./test.sh.

An example of Java is shown below.

> cd java
> mvn package -Dmaven.test.skip=true
> cd ..\test
> npm install
> cd ..
> mocha test\test*.js
A basic test case is provided in the test directory. In addition, you can add any test case (`` test / test_optional.js```).