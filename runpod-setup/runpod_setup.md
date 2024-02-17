# RunPod Setup Guide

## Getting Started with RunPod

### Step 1: Sign Up or Sign In
- **Navigate to [RunPod](https://www.runpod.io/).**
  - Sign up or sign in to your account.
  - If signing up, consider adding an SSH key for added security.

### Step 2: Manage Credits
- **Check and Add Credits**
  - Locate the credit display (`$0.00` or your current balance) at the top right of the screen and click it.
  - Add a minimum of $25 to your account to ensure you have adequate credits.

### Step 3: Selecting a GPU Cloud
- **Deployment**
  - Click the home button in the navigation menu on the left.
  - At the top left of the home screen, click "GPU Cloud".
  - You will see various GPU types available for deployment. Choose one that suits your needs.
    - For cost-effectiveness, consider selecting `1x RTX A4000`, which offers 16GB of VRAM, sufficient for running models like SDXL.

### Step 4: Choose Stable Diffusion Template
- **Customize Your GPU Cloud**
  - After selecting your GPU, you will be directed to a customization screen.
  - Use the search bar on the right to search for "Stable Diffusion".
  - Select the "RunPod Stable Diffusion" template with `runpod/stable-diffusion:web-ui-10.2.1` listed underneath.
  - Review your summary and click deploy. You will be redirected to your "Pods" section after a short wait.

### Step 5: Access Your Cloud Pod
- **Connect to Your Pod**
  - In the "Pods" section, locate your "RunPod StableDiffusion" widget and click the arrow on the right to expand.
  - Click the "connect" button. A new window with connection options will appear.
    - You will see links for "Connect to HTTP Service [Port 3001]" and "Jupyter Lab [Port 8888]" (may initially display as "Not Ready").
    - It may take some time for the pod to boot up (up to 12 minutes based on experience).

### Step 6: Connect to Your Interfaces
- **Utilize Your Services**
  - Each link opens a new window; one for the SD web UI and another for the Jupyter server.

**Congratulations!** Your RunPod is now up and running. Explore the AUTO1111 tutorial or the Jupyter server tutorial for more information. If you encounter any issues, our customer support team is ready to assist.


