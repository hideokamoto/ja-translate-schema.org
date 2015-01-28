# ja-translate-schema.org
| 	Property	| 	プロパティ名	| 	Expected Type	| 	Description	| 	プロパティ概要	| 
| 	-----	| 	-----	| 	-----	| 	-----	| 	-----	| 
| 	attendee	| 	出席者	| 	"Person or  
Organization"	| 	A person or organization attending the event. Supersedes attendees.	| 	"イベントに参加する個人または組織。  
""attendees”プロパティを優先します。"	| 
| 	doorTime	| 	開場時間	| 	DateTime	| 	The time admission will commence.	| 	入場が始まる時間	| 
| 	duration	| 	期間	| 	Duration	| 	The duration of the item (movie, audio recording, event, etc.) in ISO 8601 date format.	| 	"映画やレコーディング、イベントなどの期間。  
ISO 8601の日付フォーマットで入力します。"	| 
| 	endDate	| 	終了日	| 	Date	| 	The end date and time of the item (in ISO 8601 date format).	| 	"イベントの終了日  
ISO 8601の日付フォーマットで入力します。"	| 
| 	eventStatus	| 	イベントステータス	| 	EventStatusType	| 	An eventStatus of an event represents its status; particularly useful when an event is cancelled or rescheduled.	| 	イベントのステータスを表します。イベントがキャンセルやリスケジュールされた時に有効です。	| 
| 	location	| 	場所	| 	"PostalAddress or 
Place"	| 	The location of the event, organization or action.	| 	イベントが行われている場所や組織の位置など	| 
| 	offers	| 	オファー	| 	Offer	| 	An offer to provide this item—for example, an offer to sell a product, rent the DVD of a movie, or give away tickets to an event.	| 	"イベントで提供するオファーを入力します。
例：製品の販売や映画DVDの貸出、チケット無償配布など"	| 
| 	organizer	| 	主催者	| 	"Person or   
Organization"	| 	An organizer of an Event.	| 	イベントの主催者	| 
| 	performer	| 	パフォーマー	| 	"Person or  
Organization"	| 	A performer at the event—for example, a presenter, musician, musical group or actor. Supersedes performers.	| 	"イベントの出演者を入力します。  
例えばプレゼンターやアーティストといった内容で、「performers」プロパティに優先されます。"	| 
| 	previousStartDate	| 	以前の開始日	| 	Date	| 	Used in conjunction with eventStatus for rescheduled or cancelled events. This property contains the previously scheduled start date. For rescheduled events, the startDate property should be used for the newly scheduled start date. In the (rare) case of an event that has been postponed and rescheduled multiple times, this field may be repeated.	| 	"リスケジュールやキャンセルされたイベント用に「eventStatus」と組み合わせて使用するプロパティです。  
ここには「以前の開催予定日」を入力します。  
リスケジュールされたイベントの場合、リスケジュール後の開催日は「startDate」に入力されるべきです。  
延期や複数回リスケジュールが行われた場合にはこのフィールドを繰り返して利用することができます。"	| 
| 	recordedIn	| 	記録されている場所	| 	CreativeWork	| 	"The CreativeWork that captured all or part of this Event.  
Inverse property: recordedAt."	| 	"「CreativeWork」プロパティでイベントの全体または一部を記録できます。  
CreativeWorkの「recordedAt」プロパティから逆引き可能。"	| 
| 	startDate	| 	開始日	| 	Date	| 	The start date and time of the item (in ISO 8601 date format).	| 	（ISO 8601日付形式で）イベントの開始日時。	| 
| 	subEvent	| 	サブイベント	| 	Event	| 	An Event that is part of this event. For example, a conference event includes many presentations, each of which is a subEvent of the conference. Supersedes subEvents.	| 	"このイベントはあるイベントの一部です。  
例えばカンファレンスの中のプレゼンテーションなどのことです。  
このプロパティは「subEvents」に優先します。"	| 
| 	superEvent	| 	親イベント	| 	Event	| 	An event that this event is a part of. For example, a collection of individual music performances might each have a music festival as their superEvent.	| 	"ここに記述されたイベントがイベントの親です。  
例えば、音楽祭の中で催される個々の演奏は音楽祭に対する「superEvent」となります。"	| 
| 	typicalAgeRange	| 	対象年齢	| 	Text	| 	The typical expected age range, e.g. '7-9', '11-'.	| 	対象の年齢範囲。７歳から９歳ならば「7-9」、１１歳以上ならば「11-」と記述する。	| 
| 	workPerformed	| 	公演内容	| 	CreativeWork	| 	A work performed in some event, for example a play performed in a TheaterEvent.	| 	"イベントで催された内容  
例えば劇場で公演された劇など。"	| 