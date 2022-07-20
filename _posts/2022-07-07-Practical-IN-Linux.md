---
title: Practical in Linux
date: 2022-07-07 08:30:00
tags: OS
categories: Linux

---



# தமிழில் பிராக்டிகல் லினக்ஸ் 

​		

​		தமிழில் பிராக்டிகல் லினக்ஸ் என்பது லினக்ஸ் அடிப்படையாக கொண்டு செயல்முறை பற்றிய விளக்கம் கொடுக்கின்ற ஒரு சேனல். இன்னும் உங்களுக்கு பல கேள்விகளுக்கு விடையளிக்க தொங்கப்பட்ட ஒரு சேனல் தான் இது.

1. **லினக்ஸ் என்றால் என்ன ?**

​			லினக்ஸ் என்பது யூனிக்ஸ் (UNIX) கெர்னெல் அடிப்படையாகக் கொண்டு எழுதப்பட்ட ஒரு GNU ஆப்பரேட்டிங் சிஸ்டம். இங்க யூனிக்ஸ் மற்றும் லினக்ஸ் வெவ்வேறு இயக்கும் தளம் ஆகும் ஆனால் அடிப்படையானது ஒன்று தான். யூனிக்ஸ்யில் உள்ள அனேக கமெண்ட் (கட்டளை) களையும் கட்டமைப்புயும் ஒரு சேர மாதிரி லினக்ஸ் கொண்டு உள்ளது. 

​			யூனிக்ஸ் ஆப்பரேட்டிங் சிஸ்டம் உரிமம் பெல் லபோராடிட்டிஸ் வசம் உள்ளது. யூனிக்ஸ் மற்றும் விண்டோஸ் மற்றும் ஆப்பிள் மேக் இன்னும் பல ஆப்பரேட்டிங் சிஸ்டம் உரிமத்தை நாம் பயன் படுத்த ஒரு தொகையை கொடுக்க வேண்டும் மற்றும் ஆப்பரேட்டிங் சிஸ்டம் நாம் ஒரு போதும் மாற்றம் செய்ய கூடாது. 

​			லினக்ஸ் GNU ஆப்பரேட்டிங் சிஸ்டத்தை நிறுவ மற்றும் செயல்படுத்த முற்றிலும் இலவசம் மேலும் லினக்ஸ் ஒரு ஓப்பன் சோர்ஸ் ஆப்பரேட்டிங் சிஸ்டம் ஆகும். 

​			இங்க ஓப்பன் சோர்ஸ் என்பது என்னவென்றால் இது ஒரு இலவச மென்பொருள் (ஓப்பன் சோர்ஸ் சாப்ட்வேர் ப்ரோகிராம்) ஆகும். இந்த இலவச மென்பொருளை கொண்டு நீங்கள் யாகவோ அல்லது ஒரு குழுக்கள் ஆகியும் இணைந்து உங்களுக்கான சொந்தமான கெர்னெல் அல்லது ஒரு முழு ஆப்பரேட்டிங் சிஸ்டத்தையை உருவாக்க முடியம் (உங்களுக்கு மென்பொருள் (சாப்ட்வேர் ப்ரோகிராம்) பற்றிய ஒரு புரிதல் அவசியம் ஆகும்). அதற்கு அந்த முழு ஆப்பரேட்டிங் சிஸ்டத்தையை நீங்கள் ஒரு சமூக குழுமம்யோட (கம்யூனிட்டி சப்போர்ட் ) யாகயும் அல்லது வணிகரீதி (கம்மர்ஷியல் சப்போர்ட்) யாகயும் நீங்கள் சொந்தம் கொண்டலாம். 

​			செப்டம்பர் 17, 1991 இல் லினஸ் டொர்வால்ட்ஸால் என்பவரால் லினக்ஸ் கெர்னெல் தோற்றுவீக்கப்பட்டது. லினக்ஸ் கெர்னெல் ப்ரோக்ராம்யை அவர் ஒரு பொழுதுபோக்குயாக எழுதினார். ஆனால் அவர் அந்த (லினக்ஸ் கெர்னெல் ப்ரோக்ராம்) இலவசமாக உரிமத்தை யார்வேண்டும் என்றாலும் சேர்த்தல் மற்றும் மாற்ற செய்ய அனுமதியை நமக்கு கொடுத்து உள்ளார். லினக்ஸ்யை யாருக்கும் சொந்தமில்லை. அதன் வளர்ச்சியின் பெரும்பகுதி பல குழுக்கள் மற்றும் தனிநபர்கள் பங்களித்திருந்தாலும், மிகப் பெரிய தனிப் பங்களிப்பாளர்யும் ஊதியம் பெறாத உலகத்தில் உள்ள பல்வேறு யூசர்களால் உருவாக்கபட்டது. அதனால் லினக்ஸ் முழுமையான செம்மையாக்கயப்பட்ட மற்றும் நிலையான ஒரு ஆப்பரேட்டிங் சிஸ்டத்தையை நமக்கு கிடைத்து இருக்கிறது. லினக்ஸ்யை ஒவ்வொரு நாளும் மேம்மடுத்த பட்ட ஒரு இயங்குதளம். லினக்ஸ் ஒரு மல்டி யூசர் உறுப்பினர்களை அனுமதிக்கும் மற்றும் மல்டி டாஸ்கிங்யை செய்யும் (ஒரே நேரத்தில் பலவைகையான வேலையை செய்வது) மற்றும் உள்ளமைக்கப்பட்ட நெட்வொர்க்கிங் மற்றும் சர்வீஸ் செயல் முறைகளை ஓழுங்கப்படுத்த ஒரு முறை தான் டிமன் (daemons) ஆகும் 

