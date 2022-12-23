## Road Damage Detection & Classification : Part 2

### Intro
This is a continuation of the road damage detection & classification project from [here](https://github.com/zahraahnd/road-crack-detection). The previous section mainly discussed model training and inferencing, now we go deeper into post-processing result data with analytics-based approach using streamlit integration

# Data Post-Processing
Apart from image and video data, data retrieved from memory is still raw with a rather messy format, so we need to do the cleaning process to formatting and converting into a CSV file. 

```markdown
```

The result is a CSV file with a list of detected objects with fields including information of date, city, road name, STA, long, lat, xmin, ymin, xmax, ymax, label, and confidence score

