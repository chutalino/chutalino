- 👋 Hi, I’m @chutalino
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
chutalino/chutalino is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
https://docs.github.com/en/codespaces/guidesRemove iframe attributes when the modal has finished being hidden from the user
      $("#videoModal").on("hidden.bs.modal", function() {
          $("#videoModal iframe").removeAttr("src allow");
      });
    });
  </script>
