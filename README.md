# SOCRATIS: A benchmark of diverse open-ended emotional reactions to image-caption pairs.

`imCaptionEmotionExplanation_formatted.json` contains the data in the following format:

```
{
    unique_id: [[image_path, caption, emotions, explanations, anonymized_demographics], ...]
}
```

The `unique_id` is a unique id for a image-caption pair. Each `unique_id` key has a list of entries from diverse workers.

Each entry consists of the emotions and the explanations for feeling that emotion. Demographics may be missing for many annotations since they were optional and some workers opted to not disclose it. All data is anonymized. 

The images are at: https://drive.google.com/file/d/1J8SiUEfKqc5rfxE1nwZUrG1Hcz7Djc3G/view?usp=sharing. 