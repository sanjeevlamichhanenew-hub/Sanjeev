// script.js - Academic Website JavaScript

// Data definitions at the beginning
const academicPrograms = [
    {
        "id": 1,
        "title": "Computer Science",
        "description": "Bachelor of Science in Computer Science with specializations in AI, Cybersecurity, and Software Engineering.",
        "level": "Undergraduate",
        "duration": "4 years",
        "image": "https://picsum.photos/400/300?random=6"
    },
    {
        "id": 2,
        "title": "Business Administration",
        "description": "MBA program focusing on leadership, entrepreneurship, and global business strategies.",
        "level": "Graduate",
        "duration": "2 years",
        "image": "https://picsum.photos/400/300?random=7"
    },
    {
        "id": 3,
        "title": "Biomedical Engineering",
        "description": "Interdisciplinary program combining engineering principles with medical sciences.",
        "level": "Undergraduate",
        "duration": "4 years",
        "image": "https://picsum.photos/400/300?random=8"
    },
    {
        "id": 4,
        "title": "Psychology",
        "description": "Comprehensive study of human behavior, cognition, and mental processes.",
        "level": "Graduate",
        "duration": "2-3 years",
        "image": "https://picsum.photos/400/300?random=9"
    },
    {
        "id": 5,
        "title": "Environmental Science",
        "description": "Focus on sustainability, conservation, and environmental policy.",
        "level": "Undergraduate",
        "duration": "4 years",
        "image": "https://picsum.photos/400/300?random=10"
    },
    {
        "id": 6,
        "title": "Data Science",
        "description": "Advanced program in statistical analysis, machine learning, and big data technologies.",
        "level": "Doctoral",
        "duration": "4-5 years",
        "image": "https://picsum.photos/400/300?random=11"
    }
];

const upcomingEvents = [
    {
        "id": 1,
        "title": "Open House Day",
        "date": "2024-03-15",
        "time": "10:00 AM - 4:00 PM",
        "location": "Main Campus",
        "description": "Explore our campus, meet faculty, and learn about our programs."
    },
    {
        "id": 2,
        "title": "Research Symposium",
        "date": "2024-03-20",
        "time": "9:00 AM - 5:00 PM",
        "location": "Science Building",
        "description": "Annual showcase of student and faculty research projects."
    },
    {
        "id": 3,
        "title": "Career Fair",
        "date": "2024-03-25",
        "time": "11:00 AM - 3:00 PM",
        "location": "Student Union",
        "description": "Connect with top employers and explore career opportunities."
    },
    {
        "id": 4,
        "title": "Alumni Networking",
        "date": "2024-04-05",
        "time": "6:00 PM - 9:00 PM",
        "location": "University Hall",
        "description": "Network with successful alumni from various industries."
    }
];

// DOM Elements
const mobileMenuBtn = document.getElementById("mobileMenuBtn");
const navMenu = document.getElementById("navMenu");
const searchBtn = document.getElementById("searchBtn");
const searchModal = document.getElementById("searchModal");
const closeSearch = document.getElementById("closeSearch");
const searchInput = document.getElementById("searchInput");
const searchSubmit = document.getElementById("searchSubmit");
const applyNowBtn = document.getElementById("applyNowBtn");
const applicationModal = document.getElementById("applicationModal");
const closeModal = document.getElementById("closeModal");
const applicationForm = document.getElementById("applicationForm");
const backToTop = document.getElementById("backToTop");
const programsGrid = document.getElementById("programsGrid");
const eventsList = document.getElementById("eventsList");
const newsletterForm = document.getElementById("newsletterForm");
const cookieConsent = document.getElementById("cookieConsent");
const acceptCookies = document.getElementById("acceptCookies");
const declineCookies = document.getElementById("declineCookies");
const statNumbers = document.querySelectorAll(".stat-number");

// Initialize the website
document.addEventListener("DOMContentLoaded", function() {
    initializeWebsite();
});

function initializeWebsite() {
    // Load programs and events
    loadAcademicPrograms();
    loadUpcomingEvents();
    
    // Initialize event listeners
    setupEventListeners();
    
    // Check cookie consent
    checkCookieConsent();
    
    // Initialize animations
    initAnimations();
    
    // Initialize smooth scrolling for navigation links
    initSmoothScrolling();
}

// Event Listeners Setup
function setupEventListeners() {
    // Mobile menu toggle
    mobileMenuBtn.addEventListener("click", toggleMobileMenu);
    
    // Search functionality
    searchBtn.addEventListener("click", openSearchModal);
    closeSearch.addEventListener("click", closeSearchModal);
    searchSubmit.addEventListener("click", performSearch);
    searchInput.addEventListener("keypress", function(e) {
        if (e.key === "Enter") {
            performSearch();
        }
    });
    
    // Application modal
    applyNowBtn.addEventListener("click", openApplicationModal);
    closeModal.addEventListener("click", closeApplicationModal);
    
    // Back to top button
    backToTop.addEventListener("click", scrollToTop);
    window.addEventListener("scroll", toggleBackToTop);
    
    // Newsletter form
    newsletterForm.addEventListener("submit", handleNewsletterSubmit);
    
    // Cookie consent
    acceptCookies.addEventListener("click", acceptCookieConsent);
    declineCookies.addEventListener("click", declineCookieConsent);
    
    // Close modals when clicking outside
    window.addEventListener("click", function(event) {
        if (event.target === searchModal) {
            closeSearchModal();
        }
        if (event.target === applicationModal) {
            closeApplicationModal();
        }
    });
    
    // Dropdown menu functionality for mobile
    setupDropdownMenus();
}

// Mobile Menu Functions
function toggleMobileMenu() {
    navMenu.classList.toggle("active");
    const icon = mobileMenuBtn.querySelector("i");
    if (navMenu.classList.contains("active")) {
        icon.classList.remove("fa-bars");
        icon.classList.add("fa-times");
        document.body.style.overflow = "hidden";
    } else {
        icon.classList.remove("fa-times");
        icon.classList.add("fa-bars");
        document.body.style.overflow = "";
    }
}

// Search Functions
function openSearchModal() {
    searchModal.classList.add("active");
    searchInput.focus();
    document.body.style.overflow = "hidden";
}

function closeSearchModal() {
    searchModal.classList.remove("active");
    searchInput.value = "";
    document.body.style.overflow = "";
}

function performSearch() {
    const query = searchInput.value.trim();
    if (query) {
        alert("Searching for: " + query + "\n\nThis is a demo search function. In a real implementation, this would search the university database.");
        // In a real implementation, you would:
        // 1. Send search query to backend
        // 2. Display search results
        // 3. Handle pagination, filters, etc.
        closeSearchModal();
    } else {
        searchInput.focus();
    }
}

// Application Modal Functions
function openApplicationModal() {
    applicationModal.classList.add("active");
    document.body.style.overflow = "hidden";
}

function closeApplicationModal() {
    applicationModal.classList.remove("active");
    document.body.style.overflow = "";
}

// Back to Top Functions
function toggleBackToTop() {
    if (window.pageYOffset > 300) {
        backToTop.classList.add("visible");
    } else {
        backToTop.classList.remove("visible");
    }
}

function scrollToTop() {
    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });
}

// Load Academic Programs
function loadAcademicPrograms() {
    if (!programsGrid) return;
    
    programsGrid.innerHTML = "";
    
    academicPrograms.forEach(program => {
        const programCard = createProgramCard(program);
        programsGrid.appendChild(programCard);
    });
}

function createProgramCard(program) {
    const card = document.createElement("div");
    card.className = "program-card";
    card.innerHTML = `
        <img src="${program.image}" alt="${program.title} program" class="program-image" loading="lazy">
        <div class="program-content">
            <h3 class="program-title">${program.title}</h3>
            <p class="program-description">${program.description}</p>
            <div class="program-details">
                <span><i class="fas fa-graduation-cap"></i> ${program.level}</span>
                <span><i class="fas fa-clock"></i> ${program.duration}</span>
            </div>
            <button class="btn btn-outline program-learn-more" data-program-id="${program.id}">
                Learn More
            </button>
        </div>
    `;
    
    // Add event listener to learn more button
    const learnMoreBtn = card.querySelector(".program-learn-more");
    learnMoreBtn.addEventListener("click", function() {
        showProgramDetails(program.id);
    });
    
    return card;
}

function showProgramDetails(programId) {
    const program = academicPrograms.find(p => p.id === programId);
    if (program) {
        alert(`Program Details:\n\nTitle: ${program.title}\nLevel: ${program.level}\nDuration: ${program.duration}\n\n${program.description}\n\nThis is a demo. In a real implementation, this would show detailed program information.`);
    }
}

// Load Upcoming Events
function loadUpcomingEvents() {
    if (!eventsList) return;
    
    eventsList.innerHTML = "";
    
    upcomingEvents.forEach(event => {
        const eventCard = createEventCard(event);
        eventsList.appendChild(eventCard);
    });
}

function createEventCard(event) {
    const eventDate = new Date(event.date);
    const day = eventDate.getDate();
    const month = eventDate.toLocaleString("default", { month: "short" });
    
    const card = document.createElement("div");
    card.className = "event-card";
    card.innerHTML = `
        <div class="event-date">
            <div class="event-day">${day}</div>
            <div class="event-month">${month}</div>
        </div>
        <div class="event-content">
            <h3 class="event-title">${event.title}</h3>
            <p class="event-time"><i class="far fa-clock"></i> ${event.time}</p>
            <p class="event-location"><i class="fas fa-map-marker-alt"></i> ${event.location}</p>
            <p class="event-description">${event.description}</p>
            <button class="btn btn-primary event-register" data-event-id="${event.id}">
                Register Now
            </button>
        </div>
    `;
    
    // Add event listener to register button
    const registerBtn = card.querySelector(".event-register");
    registerBtn.addEventListener("click", function() {
        registerForEvent(event.id);
    });
    
    return card;
}

function registerForEvent(eventId) {
    const event = upcomingEvents.find(e => e.id === eventId);
    if (event) {
        alert(`Registering for: ${event.title}\n\nDate: ${event.date}\nTime: ${event.time}\nLocation: ${event.location}\n\nThis is a demo. In a real implementation, this would open a registration form.`);
    }
}

// Newsletter Form Handler
function handleNewsletterSubmit(e) {
    e.preventDefault();
    
    const emailInput = document.getElementById("newsletterEmail");
    const consentCheckbox = document.getElementById("newsletterConsent");
    const email = emailInput.value.trim();
    
    if (!email) {
        alert("Please enter your email address.");
        emailInput.focus();
        return;
    }
    
    if (!consentCheckbox.checked) {
        alert("Please agree to receive email updates.");
        consentCheckbox.focus();
        return;
    }
    
    if (!validateEmail(email)) {
        alert("Please enter a valid email address.");
        emailInput.focus();
        return;
    }
    
    // Simulate API call
    setTimeout(() => {
        alert("Thank you for subscribing to our newsletter! You will receive updates at: " + email);
        newsletterForm.reset();
    }, 500);
}

function validateEmail(email) {
    const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    return re.test(email);
}

// Cookie Consent Functions
function checkCookieConsent() {
    const consent = localStorage.getItem("cookieConsent");
    if (!consent) {
        setTimeout(() => {
            cookieConsent.classList.add("show");
        }, 1000);
    }
}

function acceptCookieConsent() {
    localStorage.setItem("cookieConsent", "accepted");
    cookieConsent.classList.remove("show");
    alert("Thank you for accepting cookies. Your preferences have been saved.");
}

function declineCookieConsent() {
    localStorage.setItem("cookieConsent", "declined");
    cookieConsent.classList.remove("show");
    alert("You have declined cookies. Some features may be limited.");
}

// Application Form Handler
if (applicationForm) {
    applicationForm.addEventListener("submit", function(e) {
        e.preventDefault();
        
        const formData = new FormData(applicationForm);
        const name = formData.get("name") || "Not provided";
        const email = formData.get("email") || "Not provided";
        const program = formData.get("program") || "Not selected";
        
        // Simulate form submission
        setTimeout(() => {
            alert(`Application Submitted Successfully!\n\nName: ${name}\nEmail: ${email}\nProgram: ${program}\n\nOur admissions team will contact you shortly.`);
            applicationForm.reset();
            closeApplicationModal();
        }, 1000);
    });
}

// Animation Functions
function initAnimations() {
    // Animate stats counter
    if (statNumbers.length > 0) {
        animateStats();
    }
    
    // Add scroll animations
    initScrollAnimations();
}

function animateStats() {
    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const statNumber = entry.target;
                const target = parseInt(statNumber.getAttribute("data-count"));
                animateCounter(statNumber, target);
                observer.unobserve(statNumber);
            }
        });
    }, { threshold: 0.5 });
    
    statNumbers.forEach(stat => observer.observe(stat));
}

function animateCounter(element, target) {
    let current = 0;
    const increment = target / 100;
    const timer = setInterval(() => {
        current += increment;
        if (current >= target) {
            element.textContent = target.toLocaleString();
            clearInterval(timer);
        } else {
            element.textContent = Math.floor(current).toLocaleString();
        }
    }, 20);
}

function initScrollAnimations() {
    const observerOptions = {
        threshold: 0.1,
        rootMargin: "0px 0px -50px 0px"
    };
    
    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add("animate-in");
            }
        });
    }, observerOptions);
    
    // Observe sections for animation
    const sections = document.querySelectorAll(".section");
    sections.forEach(section => observer.observe(section));
}

// Smooth Scrolling for Navigation Links
function initSmoothScrolling() {
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener("click", function(e) {
            e.preventDefault();
            
            const targetId = this.getAttribute("href");
            if (targetId === "#") return;
            
            const targetElement = document.querySelector(targetId);
            if (targetElement) {
                // Close mobile menu if open
                if (navMenu.classList.contains("active")) {
                    toggleMobileMenu();
                }
                
                // Scroll to target
                targetElement.scrollIntoView({
                    behavior: "smooth",
                    block: "start"
                });
            }
        });
    });
}

// Dropdown Menu Setup for Mobile
function setupDropdownMenus() {
    const dropdowns = document.querySelectorAll(".dropdown");
    
    dropdowns.forEach(dropdown => {
        const link = dropdown.querySelector(".nav-link");
        
        link.addEventListener("click", function(e) {
            if (window.innerWidth <= 768) {
                e.preventDefault();
                dropdown.classList.toggle("active");
                
                // Close other dropdowns
                dropdowns.forEach(other => {
                    if (other !== dropdown && other.classList.contains("active")) {
                        other.classList.remove("active");
                    }
                });
            }
        });
    });
    
    // Close dropdowns when clicking outside
    document.addEventListener("click", function(e) {
        if (window.innerWidth <= 768) {
            if (!e.target.closest(".dropdown")) {
                dropdowns.forEach(dropdown => {
                    dropdown.classList.remove("active");
                });
            }
        }
    });
}

// Utility Functions
function debounce(func, wait) {
    let timeout;
    return function executedFunction(...args) {
        const later = () => {
            clearTimeout(timeout);
            func(...args);
        };
        clearTimeout(timeout);
        timeout = setTimeout(later, wait);
    };
}

// Add CSS for animations
const style = document.createElement("style");
style.textContent = `
    .animate-in {
        animation: fadeInUp 0.6s ease forwards;
    }
    
    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(30px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }
    
    .program-card, .research-card, .event-card {
        opacity: 0;
    }
    
    .program-card.animate-in,
    .research-card.animate-in,
    .event-card.animate-in {
        animation: fadeInUp 0.6s ease forwards;
    }
    
    .program-card:nth-child(1) { animation-delay: 0.1s; }
    .program-card:nth-child(2) { animation-delay: 0.2s; }
    .program-card:nth-child(3) { animation-delay: 0.3s; }
    .program-card:nth-child(4) { animation-delay: 0.4s; }
    .program-card:nth-child(5) { animation-delay: 0.5s; }
    .program-card:nth-child(6) { animation-delay: 0.6s; }
`;
document.head.appendChild(style);

// Handle window resize
window.addEventListener("resize", debounce(function() {
    if (window.innerWidth > 768 && navMenu.classList.contains("active")) {
        toggleMobileMenu();
    }
}, 250));

// Error handling for images
document.addEventListener("error", function(e) {
    if (e.target.tagName === "IMG") {
        e.target.src = "https://picsum.photos/400/300?random=999";
        e.target.alt = "Image not available";
    }
}, true);
