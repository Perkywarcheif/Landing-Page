/* This prevents horizontal scroll */
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

/* Hero Section Full Screen with No Scrollbar */
.hero {
  height: 100vh;              /* Full screen height */
  width: 100%;                /* Full width without causing horizontal scroll */
  background: linear-gradient(to right, #6a11cb, #2575fc);
  color: white;
  display: flex;              /* Flex to center items */
  flex-direction: column;
  justify-content: center;    /* Vertical center */
  align-items: center;        /* Horizontal center */
  text-align: center;
  margin: 0;
  padding: 0;
}
