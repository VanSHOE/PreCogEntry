## Framing and Agenda-setting in Russian News: a Computational Analysis of Intricate Political Strategies

The paper titled "Framing and Agenda-setting in Russian News: a Computational Analysis of Intricate Political Strategies" by Anjalie Field, Doron Kliger, Shuly Wintner, Jennifer Pan, Dan Jurafsky, and Yulia Tsvetkov, provides an in-depth analysis of how framing and agenda-setting are used in Russian news to manipulate public opinion.

This paper presents an analysis of media manipulation strategies employed by the Russian newspaper Izvestia over a 13-year period. The paper begins by establishing a strong negative correlation between Russia's economic situation and the proportion of news focused on the U.S. The authors argue that this correlation is directed, with economic indicators preceding an increase in foreign news coverage, which they consider a clear case of agenda-setting. The authors identify a strategy of distraction, where the U.S. is mentioned more frequently following an economic downturn in Russia. They introduce methods for cross-lingually projecting English frames to Russian, revealing a focus on U.S. moral failings and threats. The paper offers new ways to identify subtle media manipulation strategies at the intersection of agenda-setting and framing.

The authors first use the Manual Framing Codebook (MFC) annotations to derive a lexicon of English words related to each frame in the Policy Frames Codebook. For a given frame F, they measure pointwise mutual information (PMI) for each word in the corpus. PMI is a measure of how much knowing one of these variables reduces uncertainty about the other. They then use the 250 words with the highest PMI as the base framing lexicon for each frame. The authors then apply a distant supervision method to project these English framing annotations onto their Russian corpus.

The authors then use these framing lexicons to identify the presence of any frames in a document. They define a frame to be present in a document if any annotator identified the frame, and use this as gold standard test data. In evaluating their lexicons, they consider a frame to be present in a document if the document contains at least 3 tokens from the frame’s lexicon.

The authors also evaluate the quality of their method on the Russian dataset using the intruder detection task, an established method for evaluating topic models. For each frame, they randomly sample 5 words from the framing lexicon and 1 word from the lexicon of a different frame, which has no overlap with the first lexicon. They then present these sets of words to two native Russian-speaking annotators and ask them to choose which word does not belong in the set.

Finally, the authors compare the information their framing lexicons provide with information provided by a Structured Topic Model (STM). They find that their approach is better able to capture frames the way a reader might conceptualize them, whereas topic models are useful for finding fine-grained corpus-specific topics.

### Potential Improvements

1. **Cross-Cultural Validation:**
   The paper focuses on Russian media, but the methods could be validated across different cultures and languages to ensure their robustness and generalizability. We can help in this regard by applying the methods to Indian media, which is available in both English, Hindi and variety of other langauges. This would also help us understand how media manipulation strategies vary across different cultures and languages.

2. **Inclusion of Other Media Types:**
   The study focuses on print media, but the inclusion of other media types like social media, TV, and radio could provide a more comprehensive understanding of media manipulation strategies. Social media plays a significant role in elections and can provide valuable insights into public opinion and sentiment.

### Potential Applications

The methods presented in this paper could be leveraged to understand media manipulation strategies in the context of the 2024 elections. By analyzing the framing and agenda-setting in news articles, we could gain insights into how public opinion is being shaped and manipulated. This could help in developing strategies to counter misinformation and research further into how media manipulation strategies vary across different states of India.

1. **Frame Analysis:**

   - The paper introduces a method for cross-lingual projection of framing annotations.
   - In the context of elections, understanding framing can help us identify how different media outlets are presenting candidates and issues.
   - The MFC provides a set of common frames used in media for a broad range of issues. These frames can be used to identify how different media outlets are presenting candidates and issues in the election. For example, one media outlet might frame a candidate as a champion of the working class, while another might frame the same candidate as inexperienced.

2. **Agenda-Setting:**

   - The paper also explores the concept of agenda-setting, which refers to the selection of topics that media outlets choose to cover.
   - In the context of elections, understanding agenda-setting can help us identify what issues media outlets are highlighting and which ones they are ignoring.

3. **Media Manipulation Strategies:**

   - The paper identifies a strategy of distraction, where the media mentions the U.S. more frequently following an economic downturn in Russia.
   - In the context of elections, understanding such media manipulation strategies can help us identify when media outlets might be trying to distract the public from certain issues or events.

4. **Cross-Lingual Analysis:**
   - The paper introduces methods for cross-lingually projecting English frames to Russian.
   - In the context of elections, this could be useful for understanding how media manipulation strategies are being employed in different languages such as in Hindi, and other local languages in which annotated data is not available.

The MFC provides a set of common frames used in media for a broad range of issues. These frames can be used to identify how different media outlets are presenting candidates and issues in the election. For example, one media outlet might frame a candidate as a champion of the working class, while another might frame the same candidate as inexperienced.

### Potential Project Ideas

1. **Fake News and Bias Detection**: Develop a system to detect fake news and misinformation related to the elections. This could involve training a machine learning model on a dataset of known fake news articles. We could also analyze news articles to detect media bias in election coverage. This could involve comparing the coverage of different candidates or parties by different news outlets.

2. **Predicting Election Outcomes**: Use historical election data and current trends to predict the outcome of the elections. This could involve developing a machine learning model that takes into account factors like the popularity of candidates, economic indicators, and social issues.

3. **Network Analysis of Election Influence**: Analyze the network of influencers in the election, such as politicians, celebrities, and other public figures. This could involve studying their social media networks to see who has the most influence on public opinion and analyze the impact of different election campaigns on public opinion and voting behavior. This could involve studying changes in public opinion before and after major campaign events or advertisements.
