<table><tr><th>	Property	</th><th>	プロパティ名	</th><th>	Expected Type	</th><th>	Description	</th><th>	プロパティ概要	</th></tr>
<tr><td>	attendee	</td><td>	出席者	</td><td>	"Person or 
Organization"	</td><td>	A person or organization attending the event. Supersedes attendees.	</td><td>	"イベントに参加する個人または組織。
""attendees”プロパティを優先します。"	</td></tr>
<tr><td>	doorTime	</td><td>	開場時間	</td><td>	DateTime	</td><td>	The time admission will commence.	</td><td>	入場が始まる時間	</td></tr>
<tr><td>	duration	</td><td>	期間	</td><td>	Duration	</td><td>	The duration of the item (movie, audio recording, event, etc.) in ISO 8601 date format.	</td><td>	"映画やレコーディング、イベントなどの期間。
ISO 8601の日付フォーマットで入力します。"	</td></tr>
<tr><td>	endDate	</td><td>	終了日	</td><td>	Date	</td><td>	The end date and time of the item (in ISO 8601 date format).	</td><td>	"イベントの終了日
ISO 8601の日付フォーマットで入力します。"	</td></tr>
<tr><td>	eventStatus	</td><td>	イベントステータス	</td><td>	EventStatusType	</td><td>	An eventStatus of an event represents its status; particularly useful when an event is cancelled or rescheduled.	</td><td>	イベントのステータスを表します。イベントがキャンセルやリスケジュールされた時に有効です。	</td></tr>
<tr><td>	location	</td><td>	場所	</td><td>	"PostalAddress or 
Place"	</td><td>	The location of the event, organization or action.	</td><td>	イベントが行われている場所や組織の位置など	</td></tr>
<tr><td>	offers	</td><td>	オファー	</td><td>	Offer	</td><td>	An offer to provide this item—for example, an offer to sell a product, rent the DVD of a movie, or give away tickets to an event.	</td><td>	"イベントで提供するオファーを入力します。
例：製品の販売や映画DVDの貸出、チケット無償配布など"	</td></tr>
<tr><td>	organizer	</td><td>	主催者	</td><td>	"Person or 
Organization"	</td><td>	An organizer of an Event.	</td><td>	イベントの主催者	</td></tr>
<tr><td>	performer	</td><td>	パフォーマー	</td><td>	"Person or 
Organization"	</td><td>	A performer at the event—for example, a presenter, musician, musical group or actor. Supersedes performers.	</td><td>	"イベントの出演者を入力します。
例えばプレゼンターやアーティストといった内容で、「performers」プロパティに優先されます。"	</td></tr>
<tr><td>	previousStartDate	</td><td>	以前の開始日	</td><td>	Date	</td><td>	Used in conjunction with eventStatus for rescheduled or cancelled events. This property contains the previously scheduled start date. For rescheduled events, the startDate property should be used for the newly scheduled start date. In the (rare) case of an event that has been postponed and rescheduled multiple times, this field may be repeated.	</td><td>	"リスケジュールやキャンセルされたイベント用に「eventStatus」と組み合わせて使用するプロパティです。
ここには「以前の開催予定日」を入力します。
リスケジュールされたイベントの場合、リスケジュール後の開催日は「startDate」に入力されるべきです。
延期や複数回リスケジュールが行われた場合にはこのフィールドを繰り返して利用することができます。"	</td></tr>
<tr><td>	recordedIn	</td><td>	記録されている場所	</td><td>	CreativeWork	</td><td>	"The CreativeWork that captured all or part of this Event.
Inverse property: recordedAt."	</td><td>	"「CreativeWork」プロパティでイベントの全体または一部を記録できます。
CreativeWorkの「recordedAt」プロパティから逆引き可能。"	</td></tr>
<tr><td>	startDate	</td><td>	開始日	</td><td>	Date	</td><td>	The start date and time of the item (in ISO 8601 date format).	</td><td>	（ISO 8601日付形式で）イベントの開始日時。	</td></tr>
<tr><td>	subEvent	</td><td>	サブイベント	</td><td>	Event	</td><td>	An Event that is part of this event. For example, a conference event includes many presentations, each of which is a subEvent of the conference. Supersedes subEvents.	</td><td>	"このイベントはあるイベントの一部です。
例えばカンファレンスの中のプレゼンテーションなどのことです。
このプロパティは「subEvents」に優先します。"	</td></tr>
<tr><td>	superEvent	</td><td>	親イベント	</td><td>	Event	</td><td>	An event that this event is a part of. For example, a collection of individual music performances might each have a music festival as their superEvent.	</td><td>	"ここに記述されたイベントがイベントの親です。
例えば、音楽祭の中で催される個々の演奏は音楽祭に対する「superEvent」となります。"	</td></tr>
<tr><td>	typicalAgeRange	</td><td>	対象年齢	</td><td>	Text	</td><td>	The typical expected age range, e.g. '7-9', '11-'.	</td><td>	対象の年齢範囲。７歳から９歳ならば「7-9」、１１歳以上ならば「11-」と記述する。	</td></tr>
<tr><td>	workPerformed	</td><td>	公演内容	</td><td>	CreativeWork	</td><td>	A work performed in some event, for example a play performed in a TheaterEvent.	</td><td>	"イベントで催された内容
例えば劇場で公演された劇など。"	</td></tr>
</table>