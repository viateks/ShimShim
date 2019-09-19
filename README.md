# Time For Music

App features:
- Multi-user app that synchronises audio tracks (Tracks) on a timeline at the same time for all participants (Members), as they become part of the group (Group).
- Each member can add markers (Markers) on the timeline which will be shown at the approximate time on the timeline, this can be a Text, an Image or a "Widget" (Widget), for example, a BPM pulse 
- Users can drag predefined Tracks into a collection of tracks grouped by a gig or a rehearsal (Event) 

In Design-Time:
- Member creates a list of Tracks, complete with duration (HH:MM:SS) and BPM (NNN)
- Member can add other Members and form a Group
- Each Member in the Group can add Markers to the Track which are unique to their experience and needs
- Member can add an Event which includes: Name, Start Time (datetime), End Time (datetime), Net Duration (HH:MM:SS) and then link various Tracks from the repository into the Gig and rank them in order (Rank)

In Run-Time:
- Member can start the Event by picking a Track to play from the list associated with the Event (or otherwise from the pool of Tracks)
- All Members then get the name of the Track displayed on their device at the same time
- One Member "starts" a Track which will show the same timeline progress on all Members' display
- When a Marker is due to appear, the display of the Member that had this Marker defined will see the Marker content (Text, Image or Widget) on their Display

Future Considerations:
- Programmatically analyse the BPM from the Microphone signal and compare to the BPM defined for the track, in order to automatically  adjust the timeline displayed "on the fly", in case the BPM is slower or faster than originally defined
- Widgets that show the BPM in a non-intrusive way, alongeside the Image and/or Text markers
- Single click communication - a set of buttons displayed in the app (around the main display) that can be quickly used to share messages with the rest of the Group in run-time, such as - "Pull Back", "Build Up", "Speed Up", "Slow Down", "Look at me", "Last Bar", etc.

Sample Wireframe:
![Sample Wireframe - Sample Run-Time Screen - Singer Guitarist](https://github.com/viateks/ShimShim/blob/master/Sample%20Run-Time%20Screen%20-%20Singer%20Guitarist.png)
