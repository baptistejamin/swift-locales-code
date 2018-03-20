//
//  IsoLocales.swift
//  Crisp
//
//  Created by Baptiste Jamin on 20/03/2018.
//  Copyright © 2018 Crisp IM, Inc. All rights reserved.
//

import Foundation

struct IsoLocaleInfo {
    var name:String
    var local:String
    var alpha1:String
    var alpha2:String
    var alpha2T:String
    var alpha2B:String
    var alpha3:String
}

class IsoLocaleCodes {
    class func find( key:String ) -> IsoLocaleInfo {
        var locale = IsoLocales.allLocales.filter(  { $0.alpha1 == key.lowercased() || $0.alpha2 == key.lowercased() || $0.alpha3 == key.lowercased() } )
        
        if (locale.count > 0) {
            return locale[0]
        } else {
            return (!locale.isEmpty) ? locale[0] : IsoLocaleInfo(name: "", local: "", alpha1: "", alpha2: "", alpha2T: "", alpha2B: "", alpha3: "")
        }
    }
    
    class func searchByName( name:String ) -> IsoLocaleInfo {
        var country = IsoLocales.allLocales.filter( { $0.name.lowercased() == name.lowercased() } )
        
        return (!country.isEmpty) ? country[0] : IsoLocaleInfo(name: "", local: "", alpha1: "", alpha2: "", alpha2T: "", alpha2B: "", alpha3: "")
    }
    
    class func searchByLocal( local:String ) -> IsoLocaleInfo {
        var country = IsoLocales.allLocales.filter( { $0.local.lowercased() == local.lowercased() } )
        
        return (!country.isEmpty) ? country[0] : IsoLocaleInfo(name: "", local: "", alpha1: "", alpha2: "", alpha2T: "", alpha2B: "", alpha3: "")
    }
}


class IsoLocales {
    
    class var allLocales:Array<IsoLocaleInfo> {
        
        get {
            return [
                IsoLocaleInfo(name: "Abkhaz", local: "аҧсуа бызшәа", alpha1: "ab", alpha2: "abk", alpha2T: "abk", alpha2B: "abk", alpha3: "abk" ),
                IsoLocaleInfo(name: "Afar", local: "Afaraf", alpha1: "aa", alpha2: "aar", alpha2T: "aar", alpha2B: "aar", alpha3: "aar" ),
                IsoLocaleInfo(name: "Afrikaans", local: "Afrikaans", alpha1: "af", alpha2: "afr", alpha2T: "afr", alpha2B: "afr", alpha3: "afr" ),
                IsoLocaleInfo(name: "Akan", local: "Akan", alpha1: "ak", alpha2: "aka", alpha2T: "aka", alpha2B: "aka", alpha3: "aka" ),
                IsoLocaleInfo(name: "Albanian", local: "Shqip", alpha1: "sq", alpha2: "sqi", alpha2T: "sqi", alpha2B: "alb", alpha3: "sqi" ),
                IsoLocaleInfo(name: "Amharic", local: "አማርኛ", alpha1: "am", alpha2: "amh", alpha2T: "amh", alpha2B: "amh", alpha3: "amh" ),
                IsoLocaleInfo(name: "Arabic", local: "العربية", alpha1: "ar", alpha2: "ara", alpha2T: "ara", alpha2B: "ara", alpha3: "ara" ),
                IsoLocaleInfo(name: "Aragonese", local: "aragonés", alpha1: "an", alpha2: "arg", alpha2T: "arg", alpha2B: "arg", alpha3: "arg" ),
                IsoLocaleInfo(name: "Armenian", local: "Հայերեն", alpha1: "hy", alpha2: "hye", alpha2T: "hye", alpha2B: "arm", alpha3: "hye" ),
                IsoLocaleInfo(name: "Assamese", local: "অসমীয়া", alpha1: "as", alpha2: "asm", alpha2T: "asm", alpha2B: "asm", alpha3: "asm" ),
                IsoLocaleInfo(name: "Avaric", local: "авар мацӀ", alpha1: "av", alpha2: "ava", alpha2T: "ava", alpha2B: "ava", alpha3: "ava" ),
                IsoLocaleInfo(name: "Avestan", local: "avesta", alpha1: "ae", alpha2: "ave", alpha2T: "ave", alpha2B: "ave", alpha3: "ave" ),
                IsoLocaleInfo(name: "Aymara", local: "aymar aru", alpha1: "ay", alpha2: "aym", alpha2T: "aym", alpha2B: "aym", alpha3: "aym" ),
                IsoLocaleInfo(name: "Azerbaijani", local: "azərbaycan dili", alpha1: "az", alpha2: "aze", alpha2T: "aze", alpha2B: "aze", alpha3: "aze" ),
                IsoLocaleInfo(name: "Bambara", local: "bamanankan", alpha1: "bm", alpha2: "bam", alpha2T: "bam", alpha2B: "bam", alpha3: "bam" ),
                IsoLocaleInfo(name: "Bashkir", local: "башҡорт теле", alpha1: "ba", alpha2: "bak", alpha2T: "bak", alpha2B: "bak", alpha3: "bak" ),
                IsoLocaleInfo(name: "Basque", local: "euskara", alpha1: "eu", alpha2: "eus", alpha2T: "eus", alpha2B: "baq", alpha3: "eus" ),
                IsoLocaleInfo(name: "Belarusian", local: "беларуская мова", alpha1: "be", alpha2: "bel", alpha2T: "bel", alpha2B: "bel", alpha3: "bel" ),
                IsoLocaleInfo(name: "Bengali", local: "বাংলা", alpha1: "bn", alpha2: "ben", alpha2T: "ben", alpha2B: "ben", alpha3: "ben" ),
                IsoLocaleInfo(name: "Bihari", local: "भोजपुरी", alpha1: "bh", alpha2: "bih", alpha2T: "bih", alpha2B: "bih", alpha3: "bih" ),
                IsoLocaleInfo(name: "Bislama", local: "Bislama", alpha1: "bi", alpha2: "bis", alpha2T: "bis", alpha2B: "bis", alpha3: "bis" ),
                IsoLocaleInfo(name: "Bosnian", local: "bosanski jezik", alpha1: "bs", alpha2: "bos", alpha2T: "bos", alpha2B: "bos", alpha3: "bos" ),
                IsoLocaleInfo(name: "Breton", local: "brezhoneg", alpha1: "br", alpha2: "bre", alpha2T: "bre", alpha2B: "bre", alpha3: "bre" ),
                IsoLocaleInfo(name: "Bulgarian", local: "български език", alpha1: "bg", alpha2: "bul", alpha2T: "bul", alpha2B: "bul", alpha3: "bul" ),
                IsoLocaleInfo(name: "Burmese", local: "ဗမာစာ", alpha1: "my", alpha2: "mya", alpha2T: "mya", alpha2B: "bur", alpha3: "mya" ),
                IsoLocaleInfo(name: "Catalan", local: "català", alpha1: "ca", alpha2: "cat", alpha2T: "cat", alpha2B: "cat", alpha3: "cat" ),
                IsoLocaleInfo(name: "Chamorro", local: "Chamoru", alpha1: "ch", alpha2: "cha", alpha2T: "cha", alpha2B: "cha", alpha3: "cha" ),
                IsoLocaleInfo(name: "Chechen", local: "нохчийн мотт", alpha1: "ce", alpha2: "che", alpha2T: "che", alpha2B: "che", alpha3: "che" ),
                IsoLocaleInfo(name: "Chichewa", local: "chiCheŵa", alpha1: "ny", alpha2: "nya", alpha2T: "nya", alpha2B: "nya", alpha3: "nya" ),
                IsoLocaleInfo(name: "Chinese", local: "中文", alpha1: "zh", alpha2: "zho", alpha2T: "zho", alpha2B: "chi", alpha3: "zho" ),
                IsoLocaleInfo(name: "Chuvash", local: "чӑваш чӗлхи", alpha1: "cv", alpha2: "chv", alpha2T: "chv", alpha2B: "chv", alpha3: "chv" ),
                IsoLocaleInfo(name: "Cornish", local: "Kernewek", alpha1: "kw", alpha2: "cor", alpha2T: "cor", alpha2B: "cor", alpha3: "cor" ),
                IsoLocaleInfo(name: "Corsican", local: "corsu", alpha1: "co", alpha2: "cos", alpha2T: "cos", alpha2B: "cos", alpha3: "cos" ),
                IsoLocaleInfo(name: "Cree", local: "ᓀᐦᐃᔭᐍᐏᐣ", alpha1: "cr", alpha2: "cre", alpha2T: "cre", alpha2B: "cre", alpha3: "cre" ),
                IsoLocaleInfo(name: "Croatian", local: "hrvatski jezik", alpha1: "hr", alpha2: "hrv", alpha2T: "hrv", alpha2B: "hrv", alpha3: "hrv" ),
                IsoLocaleInfo(name: "Czech", local: "čeština", alpha1: "cs", alpha2: "ces", alpha2T: "ces", alpha2B: "cze", alpha3: "ces" ),
                IsoLocaleInfo(name: "Danish", local: "dansk", alpha1: "da", alpha2: "dan", alpha2T: "dan", alpha2B: "dan", alpha3: "dan" ),
                IsoLocaleInfo(name: "Divehi", local: "Divehi", alpha1: "iv", alpha2: "div", alpha2T: "div", alpha2B: "div", alpha3: "div" ),
                IsoLocaleInfo(name: "Dutch", local: "Nederlands", alpha1: "nl", alpha2: "nld", alpha2T: "nld", alpha2B: "dut", alpha3: "nld" ),
                IsoLocaleInfo(name: "Dzongkha", local: "རྫོང་ཁ", alpha1: "dz", alpha2: "dzo", alpha2T: "dzo", alpha2B: "dzo", alpha3: "dzo" ),
                IsoLocaleInfo(name: "English", local: "English", alpha1: "en", alpha2: "eng", alpha2T: "eng", alpha2B: "eng", alpha3: "eng" ),
                IsoLocaleInfo(name: "Esperanto", local: "Esperanto", alpha1: "eo", alpha2: "epo", alpha2T: "epo", alpha2B: "epo", alpha3: "epo" ),
                IsoLocaleInfo(name: "Estonian", local: "eesti", alpha1: "et", alpha2: "est", alpha2T: "est", alpha2B: "est", alpha3: "est" ),
                IsoLocaleInfo(name: "Ewe", local: "Eʋegbe", alpha1: "ee", alpha2: "ewe", alpha2T: "ewe", alpha2B: "ewe", alpha3: "ewe" ),
                IsoLocaleInfo(name: "Faroese", local: "føroyskt", alpha1: "fo", alpha2: "fao", alpha2T: "fao", alpha2B: "fao", alpha3: "fao" ),
                IsoLocaleInfo(name: "Fijian", local: "vosa Vakaviti", alpha1: "fj", alpha2: "fij", alpha2T: "fij", alpha2B: "fij", alpha3: "fij" ),
                IsoLocaleInfo(name: "Finnish", local: "suomi", alpha1: "fi", alpha2: "fin", alpha2T: "fin", alpha2B: "fin", alpha3: "fin" ),
                IsoLocaleInfo(name: "French", local: "français", alpha1: "fr", alpha2: "fra", alpha2T: "fra", alpha2B: "fre", alpha3: "fra" ),
                IsoLocaleInfo(name: "Fula", local: "Fulfulde", alpha1: "ff", alpha2: "ful", alpha2T: "ful", alpha2B: "ful", alpha3: "ful" ),
                IsoLocaleInfo(name: "Galician", local: "galego", alpha1: "gl", alpha2: "glg", alpha2T: "glg", alpha2B: "glg", alpha3: "glg" ),
                IsoLocaleInfo(name: "Georgian", local: "ქართული", alpha1: "ka", alpha2: "kat", alpha2T: "kat", alpha2B: "geo", alpha3: "kat" ),
                IsoLocaleInfo(name: "German", local: "Deutsch", alpha1: "de", alpha2: "deu", alpha2T: "deu", alpha2B: "ger", alpha3: "deu" ),
                IsoLocaleInfo(name: "Greek", local: "ελληνικά", alpha1: "el", alpha2: "ell", alpha2T: "ell", alpha2B: "gre", alpha3: "ell" ),
                IsoLocaleInfo(name: "Guaraní", local: "Avañe'ẽ", alpha1: "gn", alpha2: "grn", alpha2T: "grn", alpha2B: "grn", alpha3: "grn" ),
                IsoLocaleInfo(name: "Gujarati", local: "ગુજરાતી", alpha1: "gu", alpha2: "guj", alpha2T: "guj", alpha2B: "guj", alpha3: "guj" ),
                IsoLocaleInfo(name: "Haitian", local: "Kreyòl ayisyen", alpha1: "ht", alpha2: "hat", alpha2T: "hat", alpha2B: "hat", alpha3: "hat" ),
                IsoLocaleInfo(name: "Hausa", local: "هَوُسَ", alpha1: "ha", alpha2: "hau", alpha2T: "hau", alpha2B: "hau", alpha3: "hau" ),
                IsoLocaleInfo(name: "Hebrew", local: "עברית", alpha1: "he", alpha2: "heb", alpha2T: "heb", alpha2B: "heb", alpha3: "heb" ),
                IsoLocaleInfo(name: "Herero", local: "Otjiherero", alpha1: "hz", alpha2: "her", alpha2T: "her", alpha2B: "her", alpha3: "her" ),
                IsoLocaleInfo(name: "Hindi", local: "हिन्दी", alpha1: "hi", alpha2: "hin", alpha2T: "hin", alpha2B: "hin", alpha3: "hin" ),
                IsoLocaleInfo(name: "Hiri Motu", local: "Hiri Motu", alpha1: "ho", alpha2: "hmo", alpha2T: "hmo", alpha2B: "hmo", alpha3: "hmo" ),
                IsoLocaleInfo(name: "Hungarian", local: "magyar", alpha1: "hu", alpha2: "hun", alpha2T: "hun", alpha2B: "hun", alpha3: "hun" ),
                IsoLocaleInfo(name: "Interlingua", local: "Interlingua", alpha1: "ia", alpha2: "ina", alpha2T: "ina", alpha2B: "ina", alpha3: "ina" ),
                IsoLocaleInfo(name: "Indonesian", local: "Bahasa Indonesia", alpha1: "id", alpha2: "ind", alpha2T: "ind", alpha2B: "ind", alpha3: "ind" ),
                IsoLocaleInfo(name: "Interlingue", local: "Interlingue", alpha1: "ie", alpha2: "ile", alpha2T: "ile", alpha2B: "ile", alpha3: "ile" ),
                IsoLocaleInfo(name: "Irish", local: "Gaeilge", alpha1: "ga", alpha2: "gle", alpha2T: "gle", alpha2B: "gle", alpha3: "gle" ),
                IsoLocaleInfo(name: "Igbo", local: "Asụsụ Igbo", alpha1: "ig", alpha2: "ibo", alpha2T: "ibo", alpha2B: "ibo", alpha3: "ibo" ),
                IsoLocaleInfo(name: "Inupiaq", local: "Iñupiaq", alpha1: "ik", alpha2: "ipk", alpha2T: "ipk", alpha2B: "ipk", alpha3: "ipk" ),
                IsoLocaleInfo(name: "Ido", local: "Ido", alpha1: "io", alpha2: "ido", alpha2T: "ido", alpha2B: "ido", alpha3: "ido" ),
                IsoLocaleInfo(name: "Icelandic", local: "Íslenska", alpha1: "is", alpha2: "isl", alpha2T: "isl", alpha2B: "ice", alpha3: "isl" ),
                IsoLocaleInfo(name: "Italian", local: "italiano", alpha1: "it", alpha2: "ita", alpha2T: "ita", alpha2B: "ita", alpha3: "ita" ),
                IsoLocaleInfo(name: "Inuktitut", local: "ᐃᓄᒃᑎᑐᑦ", alpha1: "iu", alpha2: "iku", alpha2T: "iku", alpha2B: "iku", alpha3: "iku" ),
                IsoLocaleInfo(name: "Japanese", local: "日本語", alpha1: "ja", alpha2: "jpn", alpha2T: "jpn", alpha2B: "jpn", alpha3: "jpn" ),
                IsoLocaleInfo(name: "Javanese", local: "basa Jawa", alpha1: "jv", alpha2: "jav", alpha2T: "jav", alpha2B: "jav", alpha3: "jav" ),
                IsoLocaleInfo(name: "Kalaallisut", local: "kalaallisut", alpha1: "kl", alpha2: "kal", alpha2T: "kal", alpha2B: "kal", alpha3: "kal" ),
                IsoLocaleInfo(name: "Kannada", local: "ಕನ್ನಡ", alpha1: "kn", alpha2: "kan", alpha2T: "kan", alpha2B: "kan", alpha3: "kan" ),
                IsoLocaleInfo(name: "Kanuri", local: "Kanuri", alpha1: "kr", alpha2: "kau", alpha2T: "kau", alpha2B: "kau", alpha3: "kau" ),
                IsoLocaleInfo(name: "Kashmiri", local: "कश्मीरी", alpha1: "ks", alpha2: "kas", alpha2T: "kas", alpha2B: "kas", alpha3: "kas" ),
                IsoLocaleInfo(name: "Kazakh", local: "қазақ тілі", alpha1: "kk", alpha2: "kaz", alpha2T: "kaz", alpha2B: "kaz", alpha3: "kaz" ),
                IsoLocaleInfo(name: "Khmer", local: "ខ្មែរ", alpha1: "km", alpha2: "khm", alpha2T: "khm", alpha2B: "khm", alpha3: "khm" ),
                IsoLocaleInfo(name: "Kikuyu", local: "Gĩkũyũ", alpha1: "ki", alpha2: "kik", alpha2T: "kik", alpha2B: "kik", alpha3: "kik" ),
                IsoLocaleInfo(name: "Kinyarwanda", local: "Ikinyarwanda", alpha1: "rw", alpha2: "kin", alpha2T: "kin", alpha2B: "kin", alpha3: "kin" ),
                IsoLocaleInfo(name: "Kyrgyz", local: "Кыргызча", alpha1: "ky", alpha2: "kir", alpha2T: "kir", alpha2B: "kir", alpha3: "kir" ),
                IsoLocaleInfo(name: "Komi", local: "коми кыв", alpha1: "kv", alpha2: "kom", alpha2T: "kom", alpha2B: "kom", alpha3: "kom" ),
                IsoLocaleInfo(name: "Kongo", local: "Kikongo", alpha1: "kg", alpha2: "kon", alpha2T: "kon", alpha2B: "kon", alpha3: "kon" ),
                IsoLocaleInfo(name: "Korean", local: "한국어", alpha1: "ko", alpha2: "kor", alpha2T: "kor", alpha2B: "kor", alpha3: "kor" ),
                IsoLocaleInfo(name: "Kurdish", local: "Kurdî", alpha1: "ku", alpha2: "kur", alpha2T: "kur", alpha2B: "kur", alpha3: "kur" ),
                IsoLocaleInfo(name: "Kwanyama", local: "Kuanyama", alpha1: "kj", alpha2: "kua", alpha2T: "kua", alpha2B: "kua", alpha3: "kua" ),
                IsoLocaleInfo(name: "Latin", local: "latine", alpha1: "la", alpha2: "lat", alpha2T: "lat", alpha2B: "lat", alpha3: "lat" ),
                IsoLocaleInfo(name: "Luxembourgish", local: "Lëtzebuergesch", alpha1: "lb", alpha2: "ltz", alpha2T: "ltz", alpha2B: "ltz", alpha3: "ltz" ),
                IsoLocaleInfo(name: "Ganda", local: "Luganda", alpha1: "lg", alpha2: "lug", alpha2T: "lug", alpha2B: "lug", alpha3: "lug" ),
                IsoLocaleInfo(name: "Limburgish", local: "Limburgs", alpha1: "li", alpha2: "lim", alpha2T: "lim", alpha2B: "lim", alpha3: "lim" ),
                IsoLocaleInfo(name: "Lingala", local: "Lingála", alpha1: "ln", alpha2: "lin", alpha2T: "lin", alpha2B: "lin", alpha3: "lin" ),
                IsoLocaleInfo(name: "Lao", local: "ພາສາລາວ", alpha1: "lo", alpha2: "lao", alpha2T: "lao", alpha2B: "lao", alpha3: "lao" ),
                IsoLocaleInfo(name: "Lithuanian", local: "lietuvių kalba", alpha1: "lt", alpha2: "lit", alpha2T: "lit", alpha2B: "lit", alpha3: "lit" ),
                IsoLocaleInfo(name: "Luba-Katanga", local: "Tshiluba", alpha1: "lu", alpha2: "lub", alpha2T: "lub", alpha2B: "lub", alpha3: "lub" ),
                IsoLocaleInfo(name: "Latvian", local: "latviešu valoda", alpha1: "lv", alpha2: "lav", alpha2T: "lav", alpha2B: "lav", alpha3: "lav" ),
                IsoLocaleInfo(name: "Manx", local: "Gaelg", alpha1: "gv", alpha2: "glv", alpha2T: "glv", alpha2B: "glv", alpha3: "glv" ),
                IsoLocaleInfo(name: "Macedonian", local: "македонски јазик", alpha1: "mk", alpha2: "mkd", alpha2T: "mkd", alpha2B: "mac", alpha3: "mkd" ),
                IsoLocaleInfo(name: "Malagasy", local: "fiteny malagasy", alpha1: "mg", alpha2: "mlg", alpha2T: "mlg", alpha2B: "mlg", alpha3: "mlg" ),
                IsoLocaleInfo(name: "Malay", local: "bahasa Melayu", alpha1: "ms", alpha2: "msa", alpha2T: "msa", alpha2B: "may", alpha3: "msa" ),
                IsoLocaleInfo(name: "Malayalam", local: "മലയാളം", alpha1: "ml", alpha2: "mal", alpha2T: "mal", alpha2B: "mal", alpha3: "mal" ),
                IsoLocaleInfo(name: "Maltese", local: "Malti", alpha1: "mt", alpha2: "mlt", alpha2T: "mlt", alpha2B: "mlt", alpha3: "mlt" ),
                IsoLocaleInfo(name: "Māori", local: "te reo Māori", alpha1: "mi", alpha2: "mri", alpha2T: "mri", alpha2B: "mao", alpha3: "mri" ),
                IsoLocaleInfo(name: "Marathi", local: "मराठी", alpha1: "mr", alpha2: "mar", alpha2T: "mar", alpha2B: "mar", alpha3: "mar" ),
                IsoLocaleInfo(name: "Marshallese", local: "Kajin M̧ajeļ", alpha1: "mh", alpha2: "mah", alpha2T: "mah", alpha2B: "mah", alpha3: "mah" ),
                IsoLocaleInfo(name: "Mongolian", local: "монгол", alpha1: "mn", alpha2: "mon", alpha2T: "mon", alpha2B: "mon", alpha3: "mon" ),
                IsoLocaleInfo(name: "Nauru", local: "Ekakairũ Naoero", alpha1: "na", alpha2: "nau", alpha2T: "nau", alpha2B: "nau", alpha3: "nau" ),
                IsoLocaleInfo(name: "Navajo", local: "Diné bizaad", alpha1: "nv", alpha2: "nav", alpha2T: "nav", alpha2B: "nav", alpha3: "nav" ),
                IsoLocaleInfo(name: "Northern Ndebele", local: "isiNdebele", alpha1: "nd", alpha2: "nde", alpha2T: "nde", alpha2B: "nde", alpha3: "nde" ),
                IsoLocaleInfo(name: "Nepali", local: "नेपाली", alpha1: "ne", alpha2: "nep", alpha2T: "nep", alpha2B: "nep", alpha3: "nep" ),
                IsoLocaleInfo(name: "Ndonga", local: "Owambo", alpha1: "ng", alpha2: "ndo", alpha2T: "ndo", alpha2B: "ndo", alpha3: "ndo" ),
                IsoLocaleInfo(name: "Norwegian Bokmål", local: "Norsk bokmål", alpha1: "nb", alpha2: "nob", alpha2T: "nob", alpha2B: "nob", alpha3: "nob" ),
                IsoLocaleInfo(name: "Norwegian Nynorsk", local: "Norsk nynorsk", alpha1: "nn", alpha2: "nno", alpha2T: "nno", alpha2B: "nno", alpha3: "nno" ),
                IsoLocaleInfo(name: "Norwegian", local: "Norsk", alpha1: "no", alpha2: "nor", alpha2T: "nor", alpha2B: "nor", alpha3: "nor" ),
                IsoLocaleInfo(name: "Nuosu", local: "ꆈꌠ꒿ Nuosuhxop", alpha1: "ii", alpha2: "iii", alpha2T: "iii", alpha2B: "iii", alpha3: "iii" ),
                IsoLocaleInfo(name: "Southern Ndebele", local: "isiNdebele", alpha1: "nr", alpha2: "nbl", alpha2T: "nbl", alpha2B: "nbl", alpha3: "nbl" ),
                IsoLocaleInfo(name: "Occitan", local: "occitan", alpha1: "oc", alpha2: "oci", alpha2T: "oci", alpha2B: "oci", alpha3: "oci" ),
                IsoLocaleInfo(name: "Ojibwe", local: "ᐊᓂᔑᓈᐯᒧᐎᓐ", alpha1: "oj", alpha2: "oji", alpha2T: "oji", alpha2B: "oji", alpha3: "oji" ),
                IsoLocaleInfo(name: "Old Church Slavonic", local: "ѩзыкъ словѣньскъ", alpha1: "cu", alpha2: "chu", alpha2T: "chu", alpha2B: "chu", alpha3: "chu" ),
                IsoLocaleInfo(name: "Oromo", local: "Afaan Oromoo", alpha1: "om", alpha2: "orm", alpha2T: "orm", alpha2B: "orm", alpha3: "orm" ),
                IsoLocaleInfo(name: "Oriya", local: "ଓଡ଼ିଆ", alpha1: "or", alpha2: "ori", alpha2T: "ori", alpha2B: "ori", alpha3: "ori" ),
                IsoLocaleInfo(name: "Ossetian", local: "ирон æвзаг", alpha1: "os", alpha2: "oss", alpha2T: "oss", alpha2B: "oss", alpha3: "oss" ),
                IsoLocaleInfo(name: "Panjabi", local: "ਪੰਜਾਬੀ", alpha1: "pa", alpha2: "pan", alpha2T: "pan", alpha2B: "pan", alpha3: "pan" ),
                IsoLocaleInfo(name: "Pāli", local: "पाऴि", alpha1: "pi", alpha2: "pli", alpha2T: "pli", alpha2B: "pli", alpha3: "pli" ),
                IsoLocaleInfo(name: "Persian", local: "فارسی", alpha1: "fa", alpha2: "fas", alpha2T: "fas", alpha2B: "per", alpha3: "fas" ),
                IsoLocaleInfo(name: "Polish", local: "język polski", alpha1: "pl", alpha2: "pol", alpha2T: "pol", alpha2B: "pol", alpha3: "pol" ),
                IsoLocaleInfo(name: "Pashto", local: "پښتو", alpha1: "ps", alpha2: "pus", alpha2T: "pus", alpha2B: "pus", alpha3: "pus" ),
                IsoLocaleInfo(name: "Portuguese", local: "português", alpha1: "pt", alpha2: "por", alpha2T: "por", alpha2B: "por", alpha3: "por" ),
                IsoLocaleInfo(name: "Quechua", local: "Runa Simi", alpha1: "qu", alpha2: "que", alpha2T: "que", alpha2B: "que", alpha3: "que" ),
                IsoLocaleInfo(name: "Romansh", local: "rumantsch grischun", alpha1: "rm", alpha2: "roh", alpha2T: "roh", alpha2B: "roh", alpha3: "roh" ),
                IsoLocaleInfo(name: "Kirundi", local: "Ikirundi", alpha1: "rn", alpha2: "run", alpha2T: "run", alpha2B: "run", alpha3: "run" ),
                IsoLocaleInfo(name: "Romanian", local: "limba română", alpha1: "ro", alpha2: "ron", alpha2T: "ron", alpha2B: "rum", alpha3: "ron" ),
                IsoLocaleInfo(name: "Russian", local: "русский язык", alpha1: "ru", alpha2: "rus", alpha2T: "rus", alpha2B: "rus", alpha3: "rus" ),
                IsoLocaleInfo(name: "Sanskrit", local: "संस्कृतम्", alpha1: "sa", alpha2: "san", alpha2T: "san", alpha2B: "san", alpha3: "san" ),
                IsoLocaleInfo(name: "Sardinian", local: "sardu", alpha1: "sc", alpha2: "srd", alpha2T: "srd", alpha2B: "srd", alpha3: "srd" ),
                IsoLocaleInfo(name: "Sindhi", local: "सिन्धी", alpha1: "sd", alpha2: "snd", alpha2T: "snd", alpha2B: "snd", alpha3: "snd" ),
                IsoLocaleInfo(name: "Northern Sami", local: "Davvisámegiella", alpha1: "se", alpha2: "sme", alpha2T: "sme", alpha2B: "sme", alpha3: "sme" ),
                IsoLocaleInfo(name: "Samoan", local: "gagana fa'a Samoa", alpha1: "sm", alpha2: "smo", alpha2T: "smo", alpha2B: "smo", alpha3: "smo" ),
                IsoLocaleInfo(name: "Sango", local: "yângâ tî sängö", alpha1: "sg", alpha2: "sag", alpha2T: "sag", alpha2B: "sag", alpha3: "sag" ),
                IsoLocaleInfo(name: "Serbian", local: "српски језик", alpha1: "sr", alpha2: "srp", alpha2T: "srp", alpha2B: "srp", alpha3: "srp" ),
                IsoLocaleInfo(name: "Gaelic", local: "Gàidhlig", alpha1: "gd", alpha2: "gla", alpha2T: "gla", alpha2B: "gla", alpha3: "gla" ),
                IsoLocaleInfo(name: "Shona", local: "chiShona", alpha1: "sn", alpha2: "sna", alpha2T: "sna", alpha2B: "sna", alpha3: "sna" ),
                IsoLocaleInfo(name: "Sinhala", local: "සිංහල", alpha1: "si", alpha2: "sin", alpha2T: "sin", alpha2B: "sin", alpha3: "sin" ),
                IsoLocaleInfo(name: "Slovak", local: "slovenčina", alpha1: "sk", alpha2: "slk", alpha2T: "slk", alpha2B: "slo", alpha3: "slk" ),
                IsoLocaleInfo(name: "Slovene", local: "slovenski jezik", alpha1: "sl", alpha2: "slv", alpha2T: "slv", alpha2B: "slv", alpha3: "slv" ),
                IsoLocaleInfo(name: "Somali", local: "Soomaaliga", alpha1: "so", alpha2: "som", alpha2T: "som", alpha2B: "som", alpha3: "som" ),
                IsoLocaleInfo(name: "Southern Sotho", local: "Sesotho", alpha1: "st", alpha2: "sot", alpha2T: "sot", alpha2B: "sot", alpha3: "sot" ),
                IsoLocaleInfo(name: "Spanish", local: "español", alpha1: "es", alpha2: "spa", alpha2T: "spa", alpha2B: "spa", alpha3: "spa" ),
                IsoLocaleInfo(name: "Sundanese", local: "Basa Sunda", alpha1: "su", alpha2: "sun", alpha2T: "sun", alpha2B: "sun", alpha3: "sun" ),
                IsoLocaleInfo(name: "Swahili", local: "Kiswahili", alpha1: "sw", alpha2: "swa", alpha2T: "swa", alpha2B: "swa", alpha3: "swa" ),
                IsoLocaleInfo(name: "Swati", local: "SiSwati", alpha1: "ss", alpha2: "ssw", alpha2T: "ssw", alpha2B: "ssw", alpha3: "ssw" ),
                IsoLocaleInfo(name: "Swedish", local: "Svenska", alpha1: "sv", alpha2: "swe", alpha2T: "swe", alpha2B: "swe", alpha3: "swe" ),
                IsoLocaleInfo(name: "Tamil", local: "தமிழ்", alpha1: "ta", alpha2: "tam", alpha2T: "tam", alpha2B: "tam", alpha3: "tam" ),
                IsoLocaleInfo(name: "Telugu", local: "తెలుగు", alpha1: "te", alpha2: "tel", alpha2T: "tel", alpha2B: "tel", alpha3: "tel" ),
                IsoLocaleInfo(name: "Tajik", local: "тоҷикӣ", alpha1: "tg", alpha2: "tgk", alpha2T: "tgk", alpha2B: "tgk", alpha3: "tgk" ),
                IsoLocaleInfo(name: "Thai", local: "ไทย", alpha1: "th", alpha2: "tha", alpha2T: "tha", alpha2B: "tha", alpha3: "tha" ),
                IsoLocaleInfo(name: "Tigrinya", local: "ትግርኛ", alpha1: "ti", alpha2: "tir", alpha2T: "tir", alpha2B: "tir", alpha3: "tir" ),
                IsoLocaleInfo(name: "Tibetan Standard", local: "བོད་ཡིག", alpha1: "bo", alpha2: "bod", alpha2T: "bod", alpha2B: "tib", alpha3: "bod" ),
                IsoLocaleInfo(name: "Turkmen", local: "Türkmen", alpha1: "tk", alpha2: "tuk", alpha2T: "tuk", alpha2B: "tuk", alpha3: "tuk" ),
                IsoLocaleInfo(name: "Tagalog", local: "Wikang Tagalog", alpha1: "tl", alpha2: "tgl", alpha2T: "tgl", alpha2B: "tgl", alpha3: "tgl" ),
                IsoLocaleInfo(name: "Tswana", local: "Setswana", alpha1: "tn", alpha2: "tsn", alpha2T: "tsn", alpha2B: "tsn", alpha3: "tsn" ),
                IsoLocaleInfo(name: "Tonga", local: "faka Tonga", alpha1: "to", alpha2: "ton", alpha2T: "ton", alpha2B: "ton", alpha3: "ton" ),
                IsoLocaleInfo(name: "Turkish", local: "Türkçe", alpha1: "tr", alpha2: "tur", alpha2T: "tur", alpha2B: "tur", alpha3: "tur" ),
                IsoLocaleInfo(name: "Tsonga", local: "Xitsonga", alpha1: "ts", alpha2: "tso", alpha2T: "tso", alpha2B: "tso", alpha3: "tso" ),
                IsoLocaleInfo(name: "Tatar", local: "татар теле", alpha1: "tt", alpha2: "tat", alpha2T: "tat", alpha2B: "tat", alpha3: "tat" ),
                IsoLocaleInfo(name: "Twi", local: "Twi", alpha1: "tw", alpha2: "twi", alpha2T: "twi", alpha2B: "twi", alpha3: "twi" ),
                IsoLocaleInfo(name: "Tahitian", local: "Reo Tahiti", alpha1: "ty", alpha2: "tah", alpha2T: "tah", alpha2B: "tah", alpha3: "tah" ),
                IsoLocaleInfo(name: "Uyghur", local: "Uyƣurqə", alpha1: "ug", alpha2: "uig", alpha2T: "uig", alpha2B: "uig", alpha3: "uig" ),
                IsoLocaleInfo(name: "Ukrainian", local: "українська мова", alpha1: "uk", alpha2: "ukr", alpha2T: "ukr", alpha2B: "ukr", alpha3: "ukr" ),
                IsoLocaleInfo(name: "Urdu", local: "اردو", alpha1: "ur", alpha2: "urd", alpha2T: "urd", alpha2B: "urd", alpha3: "urd" ),
                IsoLocaleInfo(name: "Uzbek", local: "O‘zbek", alpha1: "uz", alpha2: "uzb", alpha2T: "uzb", alpha2B: "uzb", alpha3: "uzb" ),
                IsoLocaleInfo(name: "Venda", local: "Tshivenḓa", alpha1: "ve", alpha2: "ven", alpha2T: "ven", alpha2B: "ven", alpha3: "ven" ),
                IsoLocaleInfo(name: "Vietnamese", local: "Tiếng Việt", alpha1: "vi", alpha2: "vie", alpha2T: "vie", alpha2B: "vie", alpha3: "vie" ),
                IsoLocaleInfo(name: "Volapük", local: "Volapük", alpha1: "vo", alpha2: "vol", alpha2T: "vol", alpha2B: "vol", alpha3: "vol" ),
                IsoLocaleInfo(name: "Walloon", local: "walon", alpha1: "wa", alpha2: "wln", alpha2T: "wln", alpha2B: "wln", alpha3: "wln" ),
                IsoLocaleInfo(name: "Welsh", local: "Cymraeg", alpha1: "cy", alpha2: "cym", alpha2T: "cym", alpha2B: "wel", alpha3: "cym" ),
                IsoLocaleInfo(name: "Wolof", local: "Wollof", alpha1: "wo", alpha2: "wol", alpha2T: "wol", alpha2B: "wol", alpha3: "wol" ),
                IsoLocaleInfo(name: "Western Frisian", local: "Frysk", alpha1: "fy", alpha2: "fry", alpha2T: "fry", alpha2B: "fry", alpha3: "fry" ),
                IsoLocaleInfo(name: "Xhosa", local: "isiXhosa", alpha1: "xh", alpha2: "xho", alpha2T: "xho", alpha2B: "xho", alpha3: "xho" ),
                IsoLocaleInfo(name: "Yiddish", local: "ייִדיש", alpha1: "yi", alpha2: "yid", alpha2T: "yid", alpha2B: "yid", alpha3: "yid" ),
                IsoLocaleInfo(name: "Yoruba", local: "Yorùbá", alpha1: "yo", alpha2: "yor", alpha2T: "yor", alpha2B: "yor", alpha3: "yor" ),
                IsoLocaleInfo(name: "Zhuang", local: "Saɯ cueŋƅ", alpha1: "za", alpha2: "zha", alpha2T: "zha", alpha2B: "zha", alpha3: "zha" ),
                IsoLocaleInfo(name: "Zulu", local: "isiZulu", alpha1: "zu", alpha2: "zul", alpha2T: "zul", alpha2B: "zul", alpha3: "zul" )
            ]
        }
    }
    
}
