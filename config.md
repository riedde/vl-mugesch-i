<!--
author:   Dennis Ried

email:    dennis.ried@musikwiss.uni-halle.de

version:  1.0.0

icon: https://wcms.itz.uni-halle.de/download.php?down=57357&elem=3333420

comment:  Common metadata for all LiaScript courses in the folder

import: https://raw.githubusercontent.com/LiaTemplates/citations/main/README.md

link: ./style.css

@config.term: `Wintersemester 2025/26`
@config.university: `Martin-Luther-Universität Halle-Wittenberg`
@config.link.course: [@0](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/chapter/@1.md)
@config.preview.course: <preview-lia src="https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/chapter/@0.md"> </preview-lia>
@config.link.personen: [Zur Gesamtübersicht](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/data/personen.md)
@config.link.werke: [Zur Gesamtübersicht](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/data/werke.md)

@config.vorlesungsplan
| Sitzung | Datum | Thema |
|:--------|:------|:------|
| 1  | 22.10.2025 | @config.link.course(Organisatorisches,organisatorisches) / @config.link.course(`Musikgeschichtsschreibung`,musikgeschichtsschreibung) |
| 2  | 29.10.2025 | @config.link.course(`Um das Jahr 1600`,um1600) / @config.link.course(`Barock als Begriff`,barock_begriff) |
| 3  | 05.11.2025 | @config.link.course(`Monodie`,03a_monodie) / @config.link.course(`Entstehung der Oper`,oper_entstehung) / @config.link.course(`Seconda prattica`,seconda_prattica) |
| 4  | 12.11.2025 | @config.link.course(`Oper im Barock`,oper_barock) / @config.link.course(`Verzierungspraxis um 1600`,verzierungspraxis_um1600) |
| 5  | 19.11.2025 | @config.link.course(`Instrumentalmusik (Sonate, Suite, Concerto)`,instrumentalmusik) / @config.link.course(`Unterschiedliche Stimmungen`,stimmung) |
| 6  | 26.11.2025 | @config.link.course(`Ein Blick nach Frankreich`,frankreich_17-18Jh) |
| 7  | 03.12.2025 | @config.link.course(`Antonio Vivaldi`,vivaldi_antonio) / @config.link.course(`Die Kantate`,kantate_barock) |
| 8  | 10.12.2025 | @config.link.course(`Die Passion (Christi)`,passion_barock) |
| 9  | 17.12.2025 | @config.link.course(`Klangrede, Schreibarten, Gattungslehre (Mattheson)`,klangrede_mattheson) |
| -  | _Weihnachtspause_ | |
| 10 | 08.01.2026 | Die Begriffe @config.link.course(`"Klassik"`,klassik_begriff) und @config.link.course(`"Schule"`,schulen_mannheim_berlin) |
| 11 | 15.01.2026 | @config.link.course(`Kammermusik in der Wiener Klassik`,kammermusik_klassik) |
| 12 | 22.01.2026 | @config.link.course(`Oper und Singspiel`,oper_singspiel_klassik) |
| 13 | 29.01.2026 | @config.link.course(`Zur Biographie und Symphonik Beethovens`,beethoven_ludwig_van) |
| 14 | 05.02.2026 | @config.link.course(`Das Klavierlied`,klavierlied) / @config.link.course(`Charakterstücke`,Charakterstuecke) |
| -  | 11.02.2026 | Klausur |
@end

-->

# Config variables (overview)

```
@config.term: `Wintersemester 2025/26`
@config.university: `Martin-Luther-Universität Halle-Wittenberg`
@config.link.course: [@0](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/chapter/@1.md)
@config.link.personen: [Zur Gesamtübersicht](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/data/personen.md)
@config.link.werke: [Zur Gesamtübersicht](https://liascript.github.io/course/?https://api.allorigins.win/raw?url=https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/data/werke.md)

@config.vorlesungsplan
| Sitzung | Datum | Thema |
|:--------|:------|:------|
| 1  | 22.10.2025 | Organisatorisches / [Probleme der Musikgeschichtsschreibung](https://gitlab.informatik.uni-halle.de/muwi/vl-mugesch-i/-/raw/main/01b_musikgeschichtsschreibung.md) |
[...]
| -  | 11.02.2026 | Klausur |
@end

```

