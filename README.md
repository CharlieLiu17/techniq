# Techniq

https://gtvault-my.sharepoint.com/:p:/g/personal/bschmitz7_gatech_edu/EeDOjbpbh7hCmPXGvQcGgLABurrQdh4ltfTnTKfuu8eYqA?rtime=AVQBjvY520g

Techniq is an automatic athlete analysis app that can be used for virtually every physical sport. Techniq takes professional footage the user inputs (i.e. Steph Curry shooting a basketball) and also takes the user's own footage (i.e. themself shooting the basketball). Techniq can sync the two footages down to the frame and will then give you frame by frame comparison of the user's form against the professional. Techniq will give differences in form in degrees for all parts of the body.

## Example 

Below you can find 2 video clips: One of Charlie shooting the basketball, and one of Steph Curry shooting the basketball.


https://user-images.githubusercontent.com/50965230/177166271-6b589611-bdd9-41f7-a88c-261ab094071c.mp4

https://user-images.githubusercontent.com/50965230/177166466-c55cc1dd-3aa2-4dea-bbae-6f7618bdd61e.mp4

### Running the program on these two inputs, the result generated is a series of side-by-side frames: 

https://user-images.githubusercontent.com/50965230/177167812-9726e84a-3cda-4e6a-b74d-05a9f2544cc1.mp4

### Another example with the figure skating jump, the axel.

Initial clips:

https://user-images.githubusercontent.com/50965230/180627533-3702b083-f3a9-4df0-a0f0-0421e58e5d87.mp4

https://user-images.githubusercontent.com/50965230/180627534-76347d69-1213-4f08-b7e8-d74ed2c65a32.mp4

Output:

https://user-images.githubusercontent.com/50965230/177243187-7b14fb76-bcaa-4736-a4ec-3dd9cab62f23.mp4

Notice even with significantly different camera angles, Techniq can still correctly synchronize.

## Who is this for?

Techniq should be used by athletes and coaches alike for form training.

Athletes are never always under the watchful eye of a coach. And while this app obviously can't completely replicate a coach, it can be a pivotal tool that speedens the learning feedback loop for the athlete.

Coaches can also greatly benefit from this. An athlete and a coach have limited time together, and that time is wasted if the two of them stand around for the coach to manually sync the videos. Additionally, the app may even spot faults in form that even the coach could not detect in real-time.

## Why did we make Techniq?

Techniq was a product of a HackGT8, by Team STAC. STAC was composed of Charlie Liu, Amal Chaudry, Tina Nguyen, and Sheza Chaudhry. Charlie came up with the idea, as he was an elite figure skater in high school and had experience using Google MediaPipe. He had a personal need for the app, and even after HackGT8, continued to work on it. He currently is actively building out of the app, hoping to bring it to mobile in the near future.

## Installation

Python Version: 3.8.5

venv creation and activation:   (virtual environment (venv) lets you
install python packages in a local environment, to keep everything contained)
creation: python3 -m venv venv
activation: source venv/scripts/activate

Packages:
mediapipe       (pip install mediapipe)
cv2             (pip install opencv-python)

