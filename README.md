[RSNA Intracranial Hemorrhage Detection](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/overview) Kaggle competition starter pack

The instructions in the notebooks will take you through downloading the data, processing it, training a basic model and making a submission.

Twitter [thread](https://twitter.com/radekosmulski/status/1175156772342030337?s=20)  
Kaggle [forum post](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/discussion/109649)  
FastAi [forum post](https://forums.fast.ai/t/share-your-work-here-part-2/41392/129?u=radek)

*EDIT*: Please note, `window_and_normalize` should divide `window_width` by 2 in order to align with the 'brain window' traditionally used by radiologists for visualization. As is right now, the window is twice as wide. Good discussion on relevance of windowing to visualization / modelling in this [kaggle thread](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/discussion/109328#latest-630565)

PyTorch version: 1.2.0  
FastAi version: 1.0.58.dev0 (54b757bbfe85df4ccf391dd3da0825c441b1d2da)
