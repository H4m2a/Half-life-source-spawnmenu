# Half life source debugmode by H4m2a

DebugMenu
{
	"width"		"1250"
	"height"	"880"

		"NPC stuff"
	{
		"Security Guard"
		{
			"command"	"npc_create monster_barney"
		}
		"Scientist"
		{
			"command"	"npc_create monster_scientist"
		}
		"HECU Soldier"
		{
			"command"	"npc_create monster_human_grunt"
		}
		"Barney"
		{
			"command"	"npc_create npc_barney"
		}
		"Assassin"
		{
			"command"	"monster_human_assassin"
		}
		"Vortigaunt"
		{
			"command"	"npc_create monster_alien_slave"
		}
		"Houndeye"
		{
			"command"	"npc_create monster_houndeye"
		}
		"Zombie"
		{
			"command"	"npc_create monster_zombie"
		}
		"Gonarch"
		{
			"command"	"npc_create monster_bigmomma"
		}
		"Gargantua"
		{
			"command"	"monster_gargantua"
		}
		"Bullsquid"
		{
			"command"	"npc_create monster_bullchicken"
		}
		"Ichthyosaur"
		{
			"command"	"npc_create monster_ichthyosaur"
		}
		"Nihilant"
		{
			"command"	"npc_create monster_nihilanth"
		}
		"Tentacle"
		{
			"command"	"npc_create monster_tentacle"
		}
		"Alien Controller"
		{
			"command"	"monster_alien_controller"
		}
		"Alien Grunt"
		{
			"command"	"monster_alien_grunt"
		}
		"Osprey"
		{
			"command"	"npc_create monster_osprey"
		}
		"Flyer"
		{
			"command"	"npc_create monster_flyer"
		}
		"Xen Hair"
		{
			"command"	"npc_create monster_xen_hair"
		}
		"Xen Hull"
		{
			"command"	"npc_create monster_xen_hull"
		}
		"Xen plantlight"
		{
			"command"	"npc_create monster_xen_plantlight"
		}
		"Xen spore (large)"
		{
			"command"	"npc_create monster_xen_spore_large"
		}
		"Xen spore (medium)"
		{
			"command"	"npc_create monster_xen_spore_medium"

		}
		"Xen spore (small)"
		{
			"command"	"npc_create monster_xen_spore_small"
		}
		"Xen tree"
		{
			"command"	"npc_create monster_tree"
		}
		"Xen Ttrigger"
		{
			"command"	"npc_create xen_trigger"
		}
		"Disable/Enable AI"
		{
			"command"	"ai_disable"
		}
	}
	
"Player Stuff"
	{
			"Godmode Off/On"
		{
			"command"	"god"
		}
		"Noclip(Flymode)"
		{
			"command"	"noclip"
		}
		"Get all weapons"
		{
			"command"	"impulse 101"
		}
		"Give ammo for weapon"
		{
			"command"	"givecurrentammo"
		}
		"Notarget On/Off"
		{
			"command"	"notarget"
		}
		"Restart Map"
		{
			"command"	"restart"
		}
		"Thirdperson"
		{
			"command"	"thirdperson"
		}
		"Firstperson"
		{
			"command"	"firstperson"
		}
		"Suicide"
		{
			"command"	"kill"
		}
		"Hide HUD"
		{
			"command"	"cl_drawhud 0"
		}
		"Show HUD"
		{
			"command"	"cl_drawhud 1"
		}
		"Strip Weapons"
		{
			"command"	"ent_create  player_weaponstrip targetname stent;ent_fire stent strip;ent_fire stent kill"
		}
		"Infinite Suit Power"
		{
			"command"	"sv_infinite_aux_power 1"
		}
		"Limited Suit Power"
		{
			"command"	"sv_infinite_aux_power 0"
		}
		"Low Gravity"
		{
			"command"	"sv_gravity 50"
		}
		"Normal Gravity"
		{
			"command"	"sv_gravity 600"
		}
		"High Gravity"
		{
			"command"	"sv_gravity 2000"
		}
		"(Console)Print entity list"
		{
			"command"	"dumpentityfactories"
		}
		"Slowmo"
		{
			"command"	"host_timescale 0.2"
		}
		"Normal time"
		{
			"command"	"host_timescale 1"
		}
		"Fast time"
		{
			"command"	"host_timescale 3"
		}
		"Stop all sounds"
		{
			"command"	"stopsound"
		}
	}
}
