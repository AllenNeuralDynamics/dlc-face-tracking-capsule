# dlc-face-tracking-capsule

Port of the lim2 face-tracking pipline, using a trained deeplabcut model to ascribe annotated points to each frame in a new video. 

## model 

original model location: `/allen/aibs/technology/waynew/eye/np3_face_cam-sam_corbett-2020-03-30/dlc-models/iteration-0/np3_face_camMar30-trainset95shuffle1`

model data asset: [`np3_side_cam-sam_corbett-2020-03-31`](https://codeocean.allenneuraldynamics.org/data-assets/c2624d9c-176e-47dc-83fb-a996976eecef/np3_face_cam-sam_corbett-2020-03-30)
- ID: `c2624d9c-176e-47dc-83fb-a996976eecef`

---

Developing a capsule in codoecean is a lot like developing in a local git repository: 
- you can clone from a remote (github) to get started
- changes are tracked as commits, with commit messages
- changes can be pushed or pulled from a remote

This template sets up a starting point for processing video data with `dlc`.

## for testing
get up and running quickly by *cloning this repo* in codeocean:
- open codeocean in a new tab [here](https://codeocean.allenneuraldynamics.org/)
- hit the `+` icon (top left) and select `"New Capsule" > "Clone from Git"` and paste the URL for this repo: `https://github.com/AllenNeuralDynamics/dlc-capsule-template`
- the capsule should open at this readme

## for more-permanent, collaborative capsule development
*create a new repo*, which can serve as the remote for one or more capsules:
- open this repository on github [here](https://github.com/AllenNeuralDynamics/dlc-capsule-template)
- hit the big green button to "`Use this template`": a new repo will be created after you decide its name
- follow the cloning instructions as per [`# for testing`](#for-testing), but supply the link to your new repo
- the capsule can now pull changes from github, so you can add or edit your files anywhere, push to github, then pull in codeocean
- to push changes *from* codeocean to github:
    - generate a personal access token for your account in github
    - add it to your account in codeocean
