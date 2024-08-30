There are 3 ipynb file in the submission
    1. SelectSentense.ipynb : this file selects 1000 random sentences from the dataset
        It creates 3 files 
            1. English.txt : contains the 1000 sentences in english
            2. Hindi.txt : contains the 1000 sentences in hindi
            3. Bangla.txt : contains the 1000 sentences in bangla


    2. translation.ipynb: this file contains all model taining and Scores (except ChatGPTResponses and Scores)
        it creates:
            1. IndicTransOutput/englishToHindi.txt : contains the 1000 sentences in hindi(translated from english by IndicTrans model)
            2. IndicTransOutput/hindiToEnglish.txt : contains the 1000 sentences in English(translated from Hindi by IndicTrans model)
            3. IndicTransOutput/hindiToBangla.txt : contains the 1000 sentences in Bangla(translated from Hindi by IndicTrans model)
            4. IndicTransOutput/banglaToHindi.txt : contains the 1000 sentences in Hindi(translated from Bangla by IndicTrans model)
            5. nllbOutput/englishToHindi.txt : contains the 1000 sentences in hindi(translated from english by nllb model)
            6. nllbOutput/hindiToEnglish.txt : contains the 1000 sentences in English(translated from Hindi by nllb model)
            7. nllbOutput/hindiToBangla.txt : contains the 1000 sentences in Bangla(translated from Hindi by nllb model)
            8. nllbOutput/banglaToHindi.txt : contains the 1000 sentences in Hindi(translated from Bangla by nllb model)

    3. ChatGPTTranslation.ipynb : this file translates 50 sentenses using api of ChatGPT
        it creates:
            0. ChatGPT.txt : selects 50 sentences from data set.(Contains 50 sentences in English, Hindi and Bangla)
            1. ChatGPTResponses/englishToHindi.txt : contains the 50 sentences in hindi(translated from english by ChatGPT)
            2. ChatGPTResponses/hindiToEnglish.txt : contains the 50 sentences in English(translated from Hindi by ChatGPT)
            3. ChatGPTResponses/hindiToBangla.txt : contains the 50 sentences in Bangla(translated from Hindi by ChatGPT)
            4. ChatGPTResponses/banglaToHindi.txt : contains the 50 sentences in Hindi(translated from Bangla by ChatGPT)

    4.Learnings.ipynb : this file contains the learnings from the project

    