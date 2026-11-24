# Kalam (كلام)

**Accurate Arabic captions for video editors — powered by Whisper, built for Premiere Pro and After Effects.**

> 🚧 **Status: early development.** The first release is in progress. Star the repo to follow along, and feel free to open an issue with ideas or problems you face with Arabic captions.

[English](#english) · [العربية](#العربية)

---

## English

### The problem

If you edit videos in Arabic, you know the pain:

- **Broken Arabic in After Effects** — disconnected letters, reversed text direction, and punctuation in the wrong place.
- **Weak dialect support** — most auto-caption tools struggle with Iraqi, Gulf, and other spoken dialects.
- **Paid or low-quality tools** — the few options that exist are expensive, closed, or produce captions that need heavy manual fixing.

Captioning a single 60-second reel can take longer than editing it.

### The solution

Kalam turns your video's Arabic speech into ready-to-use captions in minutes:

1. **Transcribe** — drop in a video; Kalam uses [Whisper](https://github.com/openai/whisper) to convert Arabic speech (including dialects) into accurately timed text.
2. **Export** — get a clean `.srt` file that imports directly into Premiere Pro.
3. **Build in After Effects** — run the Kalam script to generate styled Arabic caption layers automatically, with correct letter shaping and right-to-left direction.

### Planned features

- [ ] Arabic transcription with Whisper → timed `.srt` export
- [ ] After Effects script: SRT → styled Arabic caption layers
- [ ] Word-by-word and line-by-line caption modes (reel style)
- [ ] Highlight the currently spoken word
- [ ] Ready-made caption style presets
- [ ] Improved accuracy for Iraqi and Gulf dialects
- [ ] Simple desktop interface (no command line needed)

### Who is it for?

Arabic-speaking video editors, content creators, social media agencies, and anyone who makes Reels, TikToks, or YouTube videos in Arabic.

### Contributing

Contributions are welcome — code, testing with different dialects, caption style designs, or documentation. Open an issue to start a discussion.

### License

MIT

---

## العربية

<div dir="rtl">

### المشكلة

إذا تشتغل مونتاج بالعربي، فأكيد تعرف المعاناة:

- **الكتابة العربية بـ After Effects مكسّرة**: حروف مقطعة، اتجاه مقلوب، وعلامات ترقيم بغير مكانها.
- **دعم ضعيف للهجات**: أغلب أدوات الكابشن التلقائي ما تفهم العراقي والخليجي وباقي اللهجات.
- **أدوات مدفوعة أو ضعيفة**: الخيارات الموجودة غالية أو مغلقة، أو تطلع كابشن يحتاج تصحيح يدوي كثير.

أحياناً كتابة كابشن لريل مدته دقيقة تاخذ وقت أكثر من المونتاج نفسه.

### الحل

كلام يحوّل الكلام العربي بالفيديو إلى كابشن جاهز خلال دقائق:

1. **التحويل لنص**: تحط الفيديو، وكلام يستخدم Whisper حتى يحوّل الكلام العربي، واللهجات ضمنه، إلى نص بتوقيت دقيق.
2. **التصدير**: ملف `.srt` نظيف ينفتح مباشرة بـ Premiere Pro.
3. **البناء بـ After Effects**: تشغّل سكربت كلام فيسوي طبقات كابشن عربية منسقة تلقائياً، بحروف متصلة واتجاه صحيح من اليمين لليسار.

### الميزات المخططة

- [ ] تحويل الكلام العربي لنص بـ Whisper وتصدير `.srt`
- [ ] سكربت After Effects يحوّل ملف SRT إلى طبقات كابشن عربية منسقة
- [ ] كابشن كلمة كلمة أو سطر سطر (ستايل الريلز)
- [ ] تلوين الكلمة اللي دا تنقال هسه
- [ ] ستايلات كابشن جاهزة
- [ ] دقة أعلى للهجة العراقية والخليجية
- [ ] واجهة سهلة بدون سطر أوامر

### لمن هذي الأداة؟

للمونتيرية وصنّاع المحتوى العرب، ووكالات السوشيال ميديا، وكل واحد يسوي ريلز أو تيك توك أو فيديوهات يوتيوب بالعربي.

### المساهمة

مساهماتكم مرحب بيها: كود، أو تجربة الأداة بلهجات مختلفة، أو تصاميم ستايلات كابشن، أو تحسين التوثيق. افتح Issue حتى نبدي النقاش.

### الرخصة

MIT

</div>
