# SubcorporaCarolina
Contains Carol·B and Carol·(D+B), respectively balanced and deduplicated subcorpora of the Carolina Corpus (Bea) version.

Carol·B was balanced in terms of tokens per domain from Carolina Corpus. This means that it contains approximately the same number of tokens (~60,2M) from each of Carolina’s largest domains: Legislative, Instructional, Entertainment, Journalistic, Juridical and Virtual Forum. Carol·B has, in total, 361,071,147 tokens and 5,5 GB.

Carol·(D+B) aimed at reducing the duplicated content from each of Carolina's largest domains before the balancing of tokens. We used Onion (ONe Instance ONly) corpus tool for the deduplication process, varying the setting for the duplicate content threshold as follows: 0 for Instructional, 0 for Legislative, 0.1 for Journalistic, 0.4 for Entertainment, and 0.8 for Juridical. These numbers were chosen because they resulted in the closest amount of deduplicated content to our token threshold (~60,2M). Carol·(D+B) has, in total, 361,167,265 tokens and 5,7 GB.

As the Virtual domain is the smallest of the chosen domains, it was reproduced in its integrity in Carol·(D+B) and Carol·B and served as our token threshold.

# About
Carolina is part of the Natural Language Processing of Portuguese Division (NLP2) of the Center for Artificial Intelligence (C4AI).

The complete corpus can be downloaded at: https://huggingface.co/datasets/carolina-c4ai/corpus-carolina or https://portulanclarin.net/repository/browse/carolina-general-corpus-of-contemporary-brazilian-portuguese-with-provenance-and-typology-information/f3751b34e36611ecaa5802420a870112f00a37650c304dbda703d85e14a2e945/

More about C4AI: https://c4ai.inova.usp.br/

More about Carolina: https://sites.usp.br/corpuscarolina/

# License
The corpora headers are licensed under CC BY 4.0 license.

More about the license: https://creativecommons.org/licenses/by/4.0/

It is important to note that the Carolina Corpus is composed of texts assembled from various digital repositories, each with its own license. These licenses must be observed when using the corpus. The same applies to Carol·B and Carol·(D+B).
