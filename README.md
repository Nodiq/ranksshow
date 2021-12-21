# ranksshow

plugin.yml

name: RankShower
author: Nodiq
main: pro.pixelpvp.rankshower.Main
version: 0.0.1
description: Plugin in beta sorry for bugs.

commands:
  staff:
  
  
  package pro.pixelpvp.rankshower;

import org.bukkit.command.Command;
import org.bukkit.command.CommandSender;
import org.bukkit.plugin.java.JavaPlugin;

import net.md_5.bungee.api.ChatColor;

public class Main extends JavaPlugin{

	String cuvinte = "RankShower succsessfuly enabled";
	String cuv = "RankShower succsessfuly disabled";
	
	public void onEnable(){
		System.out.print(cuvinte);
		this.getLogger().info(cuvinte);
		getCommand("staff").setExecutor(this);
	}
	
	public void onDisable(){
		System.out.print(cuv);
		this.getLogger().info(cuv);
	}
	
    @Override
    public boolean onCommand(CommandSender s, Command c, String commandLabel, String[] args) {
    	if (c.getName().endsWith("staff")){
			s.sendMessage(ChatColor.DARK_RED + "Administrators:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
			s.sendMessage(ChatColor.color + "Nodiq:");
    		return true;
    	}
    	return true;
    }	
     
}



This plugin is created by nodiq so please do not modify it as your 
