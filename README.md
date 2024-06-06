1. Export YOLOv8 model to TFJS format. Read more on the [official documentation](https://docs.ultralytics.com/tasks/detection/#export)

2. Copy `yolov8*_web_model` to `./public`

3. Update `modelName` in `App.jsx` to new model name
   ```jsx
   ...
   // model configs
   const modelName = "yolov8*"; // change to new model name
   ...
   ```
4. Done!

**Note: Custom Trained YOLOv8 Models**

Update `src/utils/labels.json` with new classes.
