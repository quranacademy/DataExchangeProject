Please refer to wiki for more information

[QuranDataExchange standards and definitions](/quranacademy/QuranDataExchange/wiki)

**2.0 Translation of Quran meaning**
Meta data for translation

| **Field**              | **Description**                       | **Required** | **Example**                                                    |
| ---------------------- | ------------------------------------- | ---------- | -------------------------------------------------------------- |
| **LanguageId**    | Language id according to ISO 639-3 standard (preffered) if not available then according to ISO 639-3 | Yes   | ru             |
| **LanguageName**  | Language name in English language   | Yes   |   Russian |                                                           |

**2.1 Translation information**

| **Field**              | **Description**                       | **Required** | **Example**                                                    |
| ---------------------- | ------------------------------------- | ---------- | -------------------------------------------------------------- |
| **TranslationName**        | Translation name in original language | Yes   | Перевод смыслов Священного Корана на русском языке             |
| **TranslationNameEnglish** | Translation name in English language  | Yes   | Translation of meanings of the Noble Quran in Russian language |
| **TranslationNameArabic**  | Translation name in Arabic language   | No   |                                                                |

**2.2 Author information**

| **Field**         | **Description**                          | **Required** | **Example**   |
| ----------------- | ---------------------------------------- | ---------- | ------------- |
| **AuthorName**       | Author’s name in original language       | Yes   | Эльмир Кулиев |
|**AuthorNameEnglish** | Author’s name in English language        | Yes   | Elmir Kuliev  |
| **AuthorNameOther**   | Author’s name in other languages         | No   |               |
| **AuthorContactInfo** | Author’s contact info email, address etc | No   |               |

**2.3 Revision information**

| **Field**    | **Description**                              | **Required** | **Example** |
| ------------ | -------------------------------------------- | ---------- | ----------- |
| **RevisionDate** | Date when last revision was made. DD/MM/YYYY | Yes   | 15/04/2018  |
| **Version**      | The number of the translation version.       | Yes   | 3.0         |
| **Frequency**    | Frequency of updates in translation          | No   | biannual    |

**2.4 Publishing information**

| **Field**          | **Description**                            | **Required** | **Example**       |
| ------------------ | ------------------------------------------ | ---------- | ----------------- |
| **ISBN**              | ISBN-13 publication number                 | No   | 978-1-56619-909-4 |
| **FirstPublishedDate** | Date of publication                        | Yes   | 03/01/2015        |
| **PublishedDate**      | Date of publication                        | Yes   | 03/01/2015        |
| **Reviewed**           | Name of person reviewed before publication | No   | Ahmad Goktas      |
| **Approved**           | Name of person responsible for publication | Yes   | Abu Adel          |

**2.4 Licensing information**
The licensing type to be indicated under [Creative Commons](https://creativecommons.org/choose/). Creative Commons provides free, easy-to-use copyright licenses to make a simple and standardized way to give the public permission to share and use the translation.

| **Field** | **Description**                                                | **Required** | **Example**                                                                                                    |
| --------- | -------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------- |
| License   | The type of license under which the translation is distributed | required   | [Attribution-NonCommercial-NoDerivatives 4.0 International](http://creativecommons.org/licenses/by-nc-nd/4.0/) |


**3.0 Quran structure meta data description**
General meta description of Quran structure to be used by developers. According to one estimate the Quran consists of 77,430 words, 18,994 unique words, 12,183 [stems](https://en.wikipedia.org/wiki/Word_stem), 3,382 [lemmas](https://en.wikipedia.org/wiki/Lemma_(morphology)) and 1,685 [roots](https://en.wikipedia.org/wiki/Root_(linguistics)). [1]

**3.1 Surah**
The Quran is divided into surahs (chapters) and further divided into ayat (verses). 

| **Field** ****          | **Description**                                                                    | **Required** | **Example**         |
| ----------------------- | ---------------------------------------------------------------------------------- | ---------- | ------------------- |
| SurahNumber             | The number of surah from min. value 1 to max. value 114                            | Yes   | 2                   |
| SurahNameOriginal       | The name of surah in original language i.e.                                        | Yes   | The Cow             |
| SurahNameTransliterated | The name of surah transliterated according to transliteration table (if available) | Yes   | Al-Baqarah          |
| SuraNameAlternative     | Alternative names for surah                                                        | No   | Mother of the Quran |

**3.2 Ayah** ****
**Āyah** (/ˈɑːjə/; Arabic: آية‎; plural: **āyāt** آيات) means "evidence" "sign"or "Miracle". In the context of Islam's principal scripture, the Quran, *ayah* is used to mean "verse", i.e. each statement or paragraph marked by a number. The [Unicode](https://en.wikipedia.org/wiki/Unicode) symbol for a Quran verse, U+06DD, is: ۝. [3]

| **Field**  | **Description**                                                 |
| ---------- | --------------------------------------------------------------- |
| AyahNumber | The number of ayah in surah from min. value 1 to max. value 286 |

**3.3 Juz (part)**
A **juzʼ** (Arabic: جُزْءْ ญุซ‎, plural أَجْزَاءْ *ajzāʼ*, literally meaning "part") is one of thirty parts of varying lengths into which the Quran is sometimes divided. A *juz* is further divided into two *ahzab* (groups), and each *hizb* (group) is in turn subdivided into four quarters, making eight quarters per *juz*, called *maqra*.

**3.4 Hizb (group)**
A *hizb* is a part of the Quran which is half the length of a *Juz*. Each *hizb* is made up of four quarters, known as *rub*. There are 60 *hizb* in the Quran

The symbol is used as a marker for the end of a chapter in Arabic calligraphy. It is represented by two overlapping squares as in the [Unicode](https://en.wikipedia.org/wiki/Unicode) glyph ۞ at U+06DE.
****
**3.6 Sajdah**
**Sujūd** (Arabic: سُجود‎, [sʊˈdʒuːd]), or **sajdah** (Arabic: سجدة‎, pronounced [[](https://en.wikipedia.org/wiki/Help:IPA/Arabic)ˈsadʒda(tu)]), is an Arabic word meaning prostration to God (Arabic: الله *Allah*) in the direction of the Kaaba at Mecca which is usually done during the daily prayers (*salat*). During the recitation of the Qur'an and during loud recitation prayers there are (15) fifteen[4] places where, sajdah is made: There are two types of Sajdah in the Qur'an which are as followings:

*1. Vajib (obligatory).* The ayas which have Vajib Sajdah are:
- Surah Sajdah: 32:15
- Surah Fusilah: 41:37
- Surah Al-Najm: 53:62
- Surah al-Alaq: 96:19

*2. Mustahab (recommended).* The ayas which have Mustahab Sajadah are:
- Surah Al-Araf: 7:206 
- Surah Al-Ra'd: 13:15
- Surah al-Nahl: 16:49,50
- Surah Bani Isreal: 17:107-109
- Surah Maryam: 19:58
- Surah Haj: 22:18
- Surah Haj: 22:77
- Surah Forqan: 25:60
- Surah Al-Naml: 27:25,26
- Surah Sad: 38:24
- Surah Inshiqaq: 84:21

In most copies of the Qur'an these are indicated by ۩ with an over-line on the word/s that invoked the prostration. Unicode symbol used for sajdah is “۩” (U+06E9)

**3.7 Ruku' (bowing or section)**
Some Muslims prefer to do 20 raka'ah every night for Salat At-Taraweeh during the month of Ramadan, that is, recite a section and go to ruku' (bowing). They had to find markers to recite a portion of the Qur'an in each Raka'ah while completing a topic. In South Asia the tradition is to complete recitation of the whole Qur'an in 27 nights. This required partitioning of the Qur'an in 27 x 20 = 540 sections excepting the Surah al-Fatiha. When such partitioning was done they ended up with 556 (+1 for Surat al-Fatiha) sections. Evidently, they did not go back to redo the partitioning to come with 540 sections. The Qur'an copies printed in South Asia have Ruku' or Section markings showing number of the ruku' within the Surah, within the Juz and ayah number within the ruku'. Traditionally, South Asian Muslims may give reference of a ayahs from the Qur'an by referring to the ruku' number and Juz number but such system is unscientific and it is not universally acceptable. Qur'an copies printed in the Arab world do not include ruku' markings.

**3.8 Manzil (stations)**
For the convenience of people who wish to read the Qur'an in a week the text may be divided into 7 portions, each portion is known as **Manzil**.[2]. The following division to 7 equal portions is by Hamza Al-Zayyat (d.156/772):


1. Al-Fatihah (chapter 1) through An-Nisa' (chapter 4) consisting of 4 surahs.
2. Al-Ma'ida (chapter 5) through At-Tawba (chapter 9) consisting of 5 surahs.
3. Yunus (chapter 10) through An-Nahl (chapter 16) consisting of 7 surahs.
4. Al Isra' (chapter 17) through Al-Furqan (chapter 25) consisting of 9 surahs.
5. Ash-Shuara' (chapter 26) through Ya-Seen (chapter 36) consisting of 11 surahs.
6. As-Saaffat (chapter 37) through Al-Hujurat (chapter 49) consisting of 13 surahs.
7. Qaf (chapter 50) through An-Nas (chapter 114) consisting of 65 surahs.


----------

[1] Dukes, Kais. ["RE: Number of Unique Words in the Quran"](http://www.mail-archive.com/comp-quran@comp.leeds.ac.uk/msg00223.html). *www.mail-archive.com*. Retrieved 29 October2012.
[2] Jaffer, Abbas (2009). *An introduction to Qurʼanic sciences = ʻUlūm al-Qurʼan*. ICAS Press. p. 16. [ISBN](https://en.wikipedia.org/wiki/International_Standard_Book_Number) [9781904063308](https://en.wikipedia.org/wiki/Special:BookSources/9781904063308).
[3]A (scanned) example of the Unicode *ayah* character is on page 3 of this [Proposal for additional Unicode characters](http://www.evertype.com/standards/iso10646/pdf/09419-encode-koranic.pdf).
[4] Islam Question and Answer: Verses in the Qur’aan where we should perform Sujood al-Tilaawah https://islamqa.info/en/5126
[5]
