# Use the official Apache HTTP Server image
FROM httpd:latest

# Add a label for autopilot
LABEL managed-by="autopilot"

# Expose port 80
EXPOSE 80

# Start the Apache HTTP server
CMD ["httpd", "-D", "FOREGROUND"]
