---
layout: default
title: Home
---
<div class="hero">
  <h2>स्वागत</h2>
  <p>यहाँ आप मुफ्त नोट्स पढ़ सकते हैं और PDF डाउनलोड कर सकते हैं — बिना किसी लॉगिन के।</p>
  <p><a class="btn" href="/courses/html-basics.html">HTML Basics पढ़ें</a></p>
</div>

<section class="about">
  <h3>About / हमारे बारे में</h3>
  <p>यह साइट विद्यार्थियों के लिए मुफ्त अध्ययन सामग्री साझा करने के लिए बनाई गयी है। आप यहाँ से नोट्स डाउनलोड कर सकते हैं और अपनी पढ़ाई के लिए उपयोग कर सकते हैं। यदि आप सामग्री जोड़ना चाहते हैं तो GitHub पर नए markdown पेज बनाकर भेज दें।</p>
</section>

<section>
  <h3>उपलब्ध कोर्स / नोट्स</h3>
  <ul>
    <li><a href="/courses/html-basics.html">HTML Basics</a></li>
    <!-- आगे नए कोर्स यहाँ जोड़ें -->
  </ul>
</section>
``` ````

Step 4 — Logo नहीं दिखे तो (optional)
- अगर आपने logo अभी upload नहीं किया है तो या logo.png नहीं है, header में वो image tag `onerror` के कारण छिप जाएगा और सिर्फ़ text title दिखेगा — फिर भी layout अच्छा दिखेगा।
- बेहतर दिखाने के लिए logo upload जरूर करें: Repo → Add file → Upload files → assets/img/logo.png → Commit changes.

Step 5 — Preview और टेस्ट
- Commit के बाद 1–2 मिनट रुकें।  
- मोबाइल ब्राउज़र में खोलें: https://barsati95.github.io  
- Home का नया रूप देखें — logo ऊपर, nav, hero और about दिखना चाहिए।  
- Course पेज और PDF डाउनलोड भी जाँचें।

Extra छोटे‑छोटे सुझाव
- अगर आप कोई color बदलना चाहें तो `_layouts/default.html` में `--accent` की value बदल दें (उदा. `#0366d6` नीला)।  
- और Images जोड़ने के लिए `assets/img/` में upload करें और Markdown में `<img src="/assets/img/your.jpg" alt="...">` से लगाएँ।  
- चाहें तो मैं आपके लिए एक छोटा favicon (16×16) और social meta tag भी जोड़ दूँ — बताइए।

यदि आप चाहें तो मैं अभी:
- 1) वही `_layouts/default.html` और `index.md` मैं आपकी repo में बना देने का step‑by‑step दूँ (कहाँ टैप करना है), या  
- 2) logo upload करने का screen‑by‑screen निर्देश दूँ, या  
- 3) एक छोटा navigation bar और footer link जोड़ दूँ — मैं direct ready code दे दूँगा।

बताइए आप कौन‑सा action अभी करना चाहेंगे — मैं एकदम step‑by‑step एक लाइन में बताऊँगा जिसे आप मोबाइल पर करके finish कर सकें।
