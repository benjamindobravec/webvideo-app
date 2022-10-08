# Videos

This example displays videos defined in file `/media/videos.json`. On left side are displayed categories, on center is displayed video with title, categories, date and description, on right side are displayed videos in selected category.

![alt text](https://github.com/benjamindobravec/webvideo-app/blob/main/screenshot.png?raw=true)


## videos.json example

```
{
    "title": "Videos",
    "categories": [
        {
            "id": "1",
            "title": "Animals"
        },
        {
            "id": "2",
            "title": "Nature"
        },
        {
            "id": "3",
            "title": "Other"
        }
    ],
    "videos": [
        {
            "title": "Big Buck Bunny",
            "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse a dui risus. Mauris tempus dui ac quam euismod porttitor. In facilisis dui lectus, convallis hendrerit leo maximus ut. Ut et dolor egestas, consequat odio rhoncus, elementum eros. Integer efficitur ac elit eget tristique. Donec luctus feugiat dapibus. Maecenas congue est in diam tempor, eu dictum urna sagittis. Vestibulum consequat odio at sapien porttitor, eu dignissim sem faucibus.",
            "url": "media/Big_Buck_Bunny_360.mp4",
            "date": "2022-01-01",
            "categories": ["1"]
        },
        {
            "title": "Big Buck Bunny",
            "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse a dui risus. Mauris tempus dui ac quam euismod porttitor. In facilisis dui lectus, convallis hendrerit leo maximus ut. Ut et dolor egestas, consequat odio rhoncus, elementum eros. Integer efficitur ac elit eget tristique. Donec luctus feugiat dapibus. Maecenas congue est in diam tempor, eu dictum urna sagittis. Vestibulum consequat odio at sapien porttitor, eu dignissim sem faucibus.",
            "url": "media/Big_Buck_Bunny_360.mp4",
            "date": "2022-05-02",
            "categories": ["1", "2"]
        },
        {
            "title": "Big Buck Bunny",
            "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse a dui risus. Mauris tempus dui ac quam euismod porttitor. In facilisis dui lectus, convallis hendrerit leo maximus ut. Ut et dolor egestas, consequat odio rhoncus, elementum eros. Integer efficitur ac elit eget tristique. Donec luctus feugiat dapibus. Maecenas congue est in diam tempor, eu dictum urna sagittis. Vestibulum consequat odio at sapien porttitor, eu dignissim sem faucibus.",
            "url": "media/Big_Buck_Bunny_360.mp4",
            "date": "2022-06-04",
            "categories": ["3"]
        },
        {
            "title": "Big Buck Bunny",
            "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse a dui risus. Mauris tempus dui ac quam euismod porttitor. In facilisis dui lectus, convallis hendrerit leo maximus ut. Ut et dolor egestas, consequat odio rhoncus, elementum eros. Integer efficitur ac elit eget tristique. Donec luctus feugiat dapibus. Maecenas congue est in diam tempor, eu dictum urna sagittis. Vestibulum consequat odio at sapien porttitor, eu dignissim sem faucibus.",
            "url": "media/Big_Buck_Bunny_360.mp4",
            "date": "2022-07-04",
            "categories": ["3"]
        }
    ]
}
```