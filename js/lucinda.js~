function showSubnav() {
    var node = document.getElementById('subnav')
    if (node.style.visibility === 'visible') {
        node.style.visibility = 'hidden';
        node.style.display = 'none';
    } else {
        node.style.visibility = 'visible';
        node.style.display = 'block';
    }
}

const sections = ["home", "water", "wts", "soap", "dissident", "unity", "cv"];
function showSection(name) {
    sections.forEach(hideSection);
    document.getElementById(name).className = "visible";
}

function hideSection(name) {
    section = document.getElementById(name);
    section.className = "invisible";
}

