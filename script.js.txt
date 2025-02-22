function startCelebration() {
    document.querySelector(".container").style.display = "none";
    document.getElementById("surprise").classList.remove("hidden");

    // Confetti Effect
    const confettiSettings = { target: 'confetti-canvas' };
    const confetti = new ConfettiGenerator(confettiSettings);
    confetti.render();
}

function showSurprise() {
    document.getElementById("extra-message").classList.remove("hidden");
}
