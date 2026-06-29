# DFA-Lexical-Analyzer
Bu proje, Deterministic Finite Automata (DFA) mantığı kullanılarak sözcük analizi (lexical analysis) gerçekleştiren interaktif bir web uygulamasıdır. Kullanıcı tarafından yüklenen JSON tabanlı DFA konfigürasyonuna göre girilen kod parçaları analiz edilir ve token türleri belirlenir.

## Özellikler

* JSON tabanlı dinamik DFA yükleme
* Lexical analysis (token tarama)
* DFA durum geçişlerinin görselleştirilmesi
* Hatalı token tespiti (Dead State)
* Token bazlı izlenen yolun gösterilmesi
* İnteraktif grafik yapısı

## Kullanılan Teknolojiler

* HTML5
* CSS3
* JavaScript
* Tailwind CSS
* Vis Network Library

## Çalışma Mantığı

1. Kullanıcı DFA konfigürasyon dosyasını (.json) yükler.
2. Analiz edilecek kod girilir.
3. Sistem kodu token’lara ayırır.
4. Her token DFA üzerinde simüle edilir.
5. Kabul edilen veya reddedilen durumlar belirlenir.
6. Token seçildiğinde DFA üzerindeki izlenen yol vurgulanır.

## Desteklenen Yapılar

* Identifier
* Number
* Operators
* Comparison Operators
* Assignment Operators
* Error Detection

## Proje Yapısı

```text id="r5wnj6"
dfa-word-scanner/
│── index.html
│── dfa_config.json
│── README.md
```

## Kullanım

1. index.html dosyasını tarayıcıda açın.

2. DFA konfigürasyon dosyasını yükleyin.

3. Kod girerek analiz yapın.

## Amaç

Bu proje, derleyici tasarımı (compiler design) derslerinde kullanılan lexical analysis mantığını görselleştirmek ve DFA yapısını daha anlaşılır hale getirmek amacıyla geliştirilmiştir.
