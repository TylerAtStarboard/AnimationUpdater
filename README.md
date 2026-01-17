# AnimationUpdater

I got sick of the animation upload workflow in studio

I hated having to publish/overwrite an animation to roblox one at a time by:
- right clicking the KeyframeSequence/opening the publish widget
- choosing my creator
- finding the animation to update
- repeating and hating my life

So I built this custom little updating/uploading widget that allows you to do this much more easily


https://github.com/user-attachments/assets/51521a8a-4c4f-4fad-b51a-32b0457e0282

# Features: 

- Bulk uploading of KeyframeSequences(create or update animations easily) 
  - For updating animations, it will automatically set the animation to the animation in the game with the same name(user setting) or "AnimationId" attribute in the KeyframeSequence
  - During publishing, the KeyframeSequences will set their "AnimationId" attribute to the newly published animation Id, making updating easy for the future
  
<img width="457" height="166" alt="image" src="https://github.com/user-attachments/assets/d23eff27-870e-4960-8d67-772ed2e4e000" />

- Preview selected animations(drag to pan)
<img width="453" height="180" alt="image" src="https://github.com/user-attachments/assets/83cfba34-ad66-4af7-84af-6c6149b1af0d" />

- Replace asset ID utility
<img width="238" height="214" alt="image" src="https://github.com/user-attachments/assets/83ba0bb4-e32b-4238-8b2c-a631820f4325" />

- Download KeyframeSequences utility(select Animation instances)
<img width="205" height="33" alt="image" src="https://github.com/user-attachments/assets/1e3286d5-084c-42bf-bc8c-06354a94ad2e" />

# How To Install/Use

- Download the latest release
https://github.com/TylerAtStarboard/AnimationUpdater/releases

- Open the plugin folder in studio
<img width="217" height="88" alt="image" src="https://github.com/user-attachments/assets/d754dc03-e0eb-4aa2-a3c6-5ddaa812f060" />

- Drag the plugin in and restart studio
<img width="802" height="43" alt="image" src="https://github.com/user-attachments/assets/89d62766-a363-4e16-a9a1-f3271c9799da" />

(Alternatively, drag the plugin directly into the workspace and right click -> save/export -> save as local plugin)

- Open the plugin widget and start selecting KeyframeSequences
<img width="57" height="62" alt="image" src="https://github.com/user-attachments/assets/97eb781f-0e9e-4e40-9277-8325f8f71499" />
