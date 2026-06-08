interface MediaPlayer {
    void play();
    void pause();
}

class AudioPlayer implements MediaPlayer {
    public void play() {
        System.out.println("Audio Playing");
    }

    public void pause() {
        System.out.println("Audio Paused");
    }
}

class VideoPlayer implements MediaPlayer {
    public void play() {
        System.out.println("Video Playing");
    }

    public void pause() {
        System.out.println("Video Paused");
    }
}

class PodcastPlayer implements MediaPlayer {
    public void play() {
        System.out.println("Podcast Playing");
    }

    public void pause() {
        System.out.println("Podcast Paused");
    }
}

public class Main {
    public static void main(String[] args) {
        MediaPlayer mp = new AudioPlayer();
        mp.play();
        mp.pause();

        mp = new VideoPlayer();
        mp.play();
        mp.pause();

        mp = new PodcastPlayer();
        mp.play();
        mp.pause();
    }
}
