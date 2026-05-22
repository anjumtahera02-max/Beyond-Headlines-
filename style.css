// ❤️ Like Post
function likePost() {
  alert("Liked ❤️");
}

// 🌙 Dark / Light Mode Toggle
function toggleMode() {
  document.body.classList.toggle("light-mode");
}

// 🔖 Save / Bookmark Post
let savedPosts = [];

function savePost(postId) {
  if (savedPosts.includes(postId)) {
    alert("Already Saved 🔖");
    return;
  }

  savedPosts.push(postId);
  alert("Post Saved 🔖");
  console.log("Saved Posts:", savedPosts);
}

// ⬇️ Download Post (basic text download)
function downloadPost(text) {
  const blob = new Blob([text], { type: "text/plain" });
  const url = URL.createObjectURL(blob);

  const a = document.createElement("a");
  a.href = url;
  a.download = "civicsphere-post.txt";
  document.body.appendChild(a);
  a.click();

  document.body.removeChild(a);
  URL.revokeObjectURL(url);
}

// 🚧 Help placeholder
function showHelp() {
  alert("Help section coming soon 🚀");
}

// 🔐 Login placeholder
function login() {
  alert("Login feature coming soon 🔐");
}

// 📝 Signup placeholder
function signup() {
  alert("Signup feature coming soon 📝");
  }
