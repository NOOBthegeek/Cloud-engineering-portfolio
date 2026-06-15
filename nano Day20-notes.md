Day 20 - Linux Logs and Troubleshooting

Commands learned:

sudo journalctl -n 20
sudo tail -20 /var/log/httpd/access_log
sudo tail -20 /var/log/httpd/error_log
sudo tail -f /var/log/httpd/access_log
sudo systemctl status httpd
systemctl --failed

What I learned:

- Linux records events in log files.
- Apache keeps access and error logs.
- journalctl displays system logs.
- tail -f monitors logs in real time.
- Logs are often the first place to look when troubleshooting.
