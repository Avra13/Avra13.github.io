const newCouple = 'Srija & Avra';

// Nov 29, 2020
const weddingDate = new Date(2023, 11, 27);

// Wedding venue: https://goo.gl/maps/5z5xX2hTYzU8VGEJ9](https://goo.gl/maps/WiBb8jbyhDo8iS127)
const weddingVenue = new Location('Baidyabati, West Bengal');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://sonali.netlify.app/')
    );
})();
