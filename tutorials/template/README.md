# Դասեր
## Նկարագրություն
Սա ձեռնարկ է, թե ինչպես ստեղծել դաս-օրինակ-առաջադրանք-ստուգում ձեւաչափի դաս։

## tutorial.json-ի ջեւաչափը՝
```json
{
    "author": {
        "name": "Arman Yeghiazaryan",
        "email": "arman@linguacode.me",
        "url": "http://otanim.com",
    },
    "tutorial": {
        "chapter": "Արտածում",
        "article": {
			"index": 1,
            "title": "նախաբան",
            "lesson": "Տերմինալում տեքստի արտածման համար օգտագործվում է **տպել** հրամանը: Օրինակ՝  \n**մուտք**՝  \n`տպել «ողջույն»`  \n**ելք**՝  \n`«ողջույն»`",
            "task": "1. Մեկնարկեք ծրագիրը, եւ տեսեք արդյունքը։  \n2. Փոփոխեք առկա արտածման տեքստը ձեր անունով, եւ մեկնարկեք ծրագիրը։",
        },
        "sourceCode": {
            "code": "տպել «ողջո՛ւյն»",
            "markers": {
				"color": "red",
				"range": [0, 6, 0, 13]
			},
            "readOnly": [
				[0, 0, 0, 5],
				[0, 14, 0, 999]
			],
            "cursor": [0, 6],
        },
        "validations": {
            "code": "/^տպել «.*»\\s*$/ig",
            "output": "/.*/ig"
        }
    },
    "sources": "դասի պատրաստման համար օգտագործված աղբյուրն է introtopython.org/syllabus.html կայքը։",
    "notes": "դասը ենթակա է ստուգման",
}
```

<ul>
	<li><b>author</b><br />
	Դասի Հեղինակի&nbsp;տվյալներն է։
	<ul>
		<li><b>name</b><br />
		Հեղինակի անունը եւ ազգանունը։</li>
		<li><b>email</b><br />
		Հեղինակի էլ․ հասցեն:</li>
		<li><b>url</b><br />
		Հեղինակի անձանական կամ սոց․ էջի հասցեն։<br />
		&nbsp;</li>
	</ul>
	</li>
	<li><strong>tutorial</strong><br />
	Դասի բոլոր պարամետրերը։<br />
	<em>(պարտադիր է լրացման)</em><br />
	&nbsp;
	<ul>
		<li><strong>chapter</strong><br />
		Դասի գլուխը։ Նույն գլխի դասները պետք է ունենան նույն գլխի chapter-ը:&nbsp;<br />
		<em>(պարտադիր է լրացման)</em><br />
		&nbsp;</li>
		<li><strong>article</strong><br />
		Դասը։<br />
		<em>(պարտադիր է լրացման)</em>
		<ul>
			<li><strong>index</strong><br />
			Դասի համարը գլխում։ Համարը պետք է լինի ամբողջ թիվ։<br />
			<em>(պարտադիր է լրացման)</em></li>
			<li><strong>title</strong><br />
			Դասի վերնագիրը։<br />
			<em>(պարտադիր է լրացման)</em></li>
			<li><strong>lesson</strong><br />
			Դասի նկարագրությունը։ <strong><a href="http://guides.github.com/features/mastering-markdown">markdown</a></strong>-ի կիրառումը թույլատրված է։<br />
			<em>(պարտադիր է լրացման)</em></li>
			<li><strong>task</strong><br />
			Դասի առաջադրանքը։ <strong><a href="http://guides.github.com/features/mastering-markdown">markdown</a></strong>-ի կիրառումը թույլատրված է։<br />
			<em>(պարտադիր է լրացման)</em><br />
			&nbsp;</li>
		</ul>
		</li>
		<li><strong>code</strong><br />
		Դասը։<br />
		<em>(պարտադիր է լրացման)</em>
		<ul>
			<li><strong>source</strong><br />
			Դասի համարը գլխում։ Համարը պետք է լինի ամբողջ թիվ։<br />
			<em>(պարտադիր է լրացման)</em><br />
			&nbsp;</li>
			<li><strong>markers</strong><br />
			Դասի վերնագիրը։<br />
			<em>(պարտադիր է լրացման)</em>
			<ul>
				<li><strong>color</strong><br />
				Դասի նկարագրությունը։ [markdown](https://guides.github.com/features/mastering-markdown/)-ի կիրառումը թույլատրված է, բացառությամբ HTML-ի։<br />
				<em>(պարտադիր է լրացման)</em></li>
				<li><strong>range</strong><br />
				Դասի նկարագրությունը։ [markdown](https://guides.github.com/features/mastering-markdown/)-ի կիրառումը թույլատրված է, բացառությամբ HTML-ի։<br />
				<em>(պարտադիր է լրացման)</em><br />
				&nbsp;</li>
			</ul>
			</li>
			<li><strong>readOnly</strong><br />
			Դասի նկարագրությունը։ [markdown](https://guides.github.com/features/mastering-markdown/)-ի կիրառումը թույլատրված է, բացառությամբ HTML-ի։<br />
			<em>(պարտադիր է լրացման)</em></li>
			<li><strong>cursor</strong><br />
			Դասի առաջադրանքը։ [markdown](https://guides.github.com/features/mastering-markdown/)-ի կիրառումը թույլատրված է, բացառությամբ HTML-ի։<br />
			<em>(պարտադիր է լրացման)</em></li>
		</ul>
		</li>
	</ul>
	</li>
</ul>
