`broadcast` अपना सन्देश देना का एक ऐसा तरीका है जिसे सभी स्प्राइट सुन सकते हैं। इसे लाउडस्पीकर पर की गई घोषणा की तरह समझें।

**Broadcasting spells**: अपने जादू की छड़ी से बटन पर क्लिक करें और मंत्र बोलें। जानिए की हर एक मंत्र पत्रों के साथ क्या करता है। [See inside](https://scratch.mit.edu/projects/518413238/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/518413238/?autostart=false" frameborder="0"></iframe>
</div>

आप `broadcast` करने के लिए सन्देश लिख सकते हैं। आप सन्देश में जो चाहें लिख सकते हैं, लेकिन इसे एक समझदार विवरण देना उपयोगी है।

+ **Broadcast** ब्लॉक को **Event** के नीचे खोजें।

+ ड्रॉप-डाउन मेन्यू (drop-down menu) में **New Message** को चुनें।

![broadcast block dropdown](images/broadcast-block.png)

+ फिर अपना संदेश लिखें।

![Create a broadcast](images/new-broadcast.png)

### प्रसारण भेजें

आपको अपना सन्देश कब `broadcast` करना है ये आप खुद चुन सकते हैं। उदाहरण के लिए:

```blocks3
जब यह स्प्राइट क्लिक होगा 
broadcast (shrink v)
```

```blocks3
जब बैकड्रॉप [level 1 v] को बदलता है
broadcast (start v)
```

### प्रसारण प्राप्त करें

स्प्राइट आपके `broadcast` पर तब ही हिलेंगे जब आप `when I receive` ब्लॉक का इस्तेमाल करेंगे। आपके एक सन्देश पर कई स्प्राइट जवाब दे सकते हैं।

आप स्प्राइट को प्रसारण संदेश प्राप्त करने पर क्या करना है बताने के लिए `when I receive` ब्लॉक के नीचे ब्लॉक्स जोड़ सकते हैं।

```blocks3
when I receive [shrink v]
माप (-10) से कम केर दें // नेगेटिव नंबर्स साइज कम केर देते हैं
```

```blocks3
when I receive [start v]
go to x: (100) y: (50)
show
```