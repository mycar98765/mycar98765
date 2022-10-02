    // Life motto
    final bool scared;
    final bool sad;
    final bool angry;

    if (scared == true) {
      stopScared();
      startHappy();
    } else if (sad == true) {
      stopSad();
      startHappy();
    } else if (angry == true) {
      stopAngry();
      startHappy();
    }
    // Let's be happy, not sad or angry
    // :)
