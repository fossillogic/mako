# 🦈 Mako
### A Command-Line Power Utility by **Fossil Logic**

Mako is a system-administration-oriented utility built to handle tasks that extend beyond Shark’s file-operation and syncing focus. It specializes in system maintenance, resource monitoring, service management, configuration auditing, and automated cleanup routines. Mako acts as a lightweight operator console for keeping systems healthy, predictable, and optimized. Ideal for admins who want fast access to diagnostic and operational controls without the overhead of heavier management suites.

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/mako.git
    cd mako
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run the Project**:

    ```sh
    mako
    ```

## **Contributing**

Interested in contributing? Please open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/mako).

## **Feedback and Support**

For issues, questions, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/mako/issues).

## **License**

This project is licensed under the [Apache 2.0 License](LICENSE).
