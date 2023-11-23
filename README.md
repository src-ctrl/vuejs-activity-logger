# Vue.js Activity Logger App & Tutorial

Welcome to the Vue.js Activity Logger repository! This comprehensive guide and application provide a hands-on tutorial for building an activity logging app with Vue.js. Whether you're a beginner or an experienced developer, this repository serves as a step-by-step guide and documentation for creating your own activity tracking application.

## Key Features
- 📖 Detailed tutorial with explanations for each step
- 🛠️ Modular Vue.js components for easy customization
- 📋 Chronological logging of various activities
- 🌐 Responsive design for seamless user experience

## Vue.js Specification

## Activities

In the Vue.js Activity Logger application, entries are referred to as "Activities." Activities have various attributes based on their nature:

### Common Attributes

- **Description:** A brief description of the activity.
- **Start:** The date and time when the activity started.
- **End:** The date and time when the activity ended. For non-timed activities, this can be null.
- **When:** The date and time when the activity occurred. This attribute is used for non-timed activities and is the same as the "Start" time for timed activities.

### Timed Activities

Some activities may have a defined time period, indicated by both **Start** and **End**. For example, an activity like "went for a run" may have both start and end times.

### Non-Timed Activities

Activities like "woke up" or "bedtime" might not have a specific duration and will be marked with just a **When**, which can be null.

## Screenshots

Here are some screenshots illustrating the Vue.js Activity Logger application:

1. **Activity List:**
   ![Activity List](/docs/screenshots/activity_list.png)
   
2. **Activity Details:**
   ![Activity Details](/docs/screenshots/activity_details.png)

3. **Adding an Activity:**
   ![Add Activity](/docs/screenshots/add_activity.png)

4. **Timed Activity Example:**
   ![Timed Activity Example](/docs/screenshots/timed_activity_example.png)

5. **Non-Timed Activity Example:**
   ![Non-Timed Activity Example](/docs/screenshots/non_timed_activity_example.png)


## How to Use
1. 📚 Follow the tutorial in the `docs` directory to build your own Vue.js Activity Logger.
2. ⚙️ Explore the application code in the `src` directory for a deep dive into Vue.js best practices.

## Contributing
👩‍💻 We welcome contributions! Whether you're fixing a bug, improving documentation, or adding a new feature, your input is valued. Check out our [contribution guidelines](link-to-contributing.md) for more details.

## License
📝 This project is licensed under the [MIT License](link-to-license.md) - feel free to use, modify, and share.

**Happy Activity Logging!** 🚀🕰️
