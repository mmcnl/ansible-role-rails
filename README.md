## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.rails
          vars:
            rails_codename: my_site
            rails_domain_name: "www.example.com"
            rails_deploy_base_dir: "/opt/my_site"
            rails_monitored_content: "My Site"

## License

MIT

