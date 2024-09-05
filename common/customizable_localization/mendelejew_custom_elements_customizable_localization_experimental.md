##############################
# MENDELEJEW CUSTOM ELEMENTS #
##############################

#by Lord R and SabbytheCat

######################

### Gallium (31) ###

#Name
mendelejew_31_gallium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
							cu:occitan ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_31_gallium
    	set_variable_mendlejew_prefix_ga_used
	}

# German options #

	text = {
		trigger = {
	  	global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
		  	any_primary_culture = {
					OR = {
				  	cu:north_german ?= this
						cu:south_german ?= this
			    }
			  }
           NOT = {
            variable_mendlejew_prefix_an_used = yes
        }
			}
		}
		localization_key = custom_element_31_alemannium
    set_variable_mendlejew_prefix_an_used = yes
	}

	text = {
		trigger = {
	  	global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
		  	any_primary_culture = {
					OR = {
				  	cu:north_german ?= this
						cu:south_german ?= this
			    }
			  }
           NOT = {
            variable_mendlejew_prefix_sa_used = yes
        }
			}
		}
		localization_key = custom_element_31_sassonium
    set_variable_mendlejew_prefix_sa_used = yes
	}

	text = {
		trigger = {
	  	global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
		  	any_primary_culture = {
					OR = {
				  	cu:north_german ?= this
						cu:south_german ?= this
				  }
			  }
           NOT = {
            variable_mendlejew_prefix_bv_used = yes
        }
			}
		}
		localization_key = custom_element_31_bavarium
    set_variable_mendlejew_prefix_bv_used = yes
	}

	text = {
		trigger = {
	  	global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
		  	any_primary_culture = {
					OR = {
				  	cu:north_german ?= this
						cu:south_german ?= this
				   }
			  }
           NOT = {
            variable_mendlejew_prefix_bv_used = yes
        }
			}
		}
		localization_key = custom_element_31_hassium
    set_variable_mendlejew_prefix_ha_used = yes
	}

# Swiss options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_hv_used = yes
        }
			}
		}
		localization_key = custom_element_31_helvetium
    set_variable_mendlejew_prefix_hv_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_gm_used = yes
        }
			}
		}
		localization_key = custom_element_31_genevium
    set_variable_mendlejew_prefix_gm_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_rh_used = yes
        }
			}
		}
		localization_key = custom_element_31_rhaetium
    set_variable_mendlejew_prefix_rh_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_tr_used = yes
        }
			}
		}
		localization_key = custom_element_31_turicum
    set_variable_mendlejew_prefix_tr_used = yes
	}

# Belgian options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:flemish ?= this
						cu:wallonian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_bg_used = yes
        }
			}
		}
		localization_key = custom_element_31_belgicum
    set_variable_mendlejew_prefix_bg_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:flemish ?= this
						cu:wallonian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_bb_used = yes
        }
			}
		}
		localization_key = custom_element_31_brabantium
    set_variable_mendlejew_prefix_bb_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:flemish ?= this
						cu:wallonian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_lb_used = yes
        }
			}
		}
		localization_key = custom_element_31_leopoldium
    set_variable_mendlejew_prefix_lb_used = yes
	}

# Italian options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_it_used = yes
        }
			}
		}
		localization_key = custom_element_31_italicum
    set_variable_mendlejew_prefix_it_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ri_used = yes
        }
			}
		}
		localization_key = custom_element_31_risogimentarium
    set_variable_mendlejew_prefix_ri_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ve_used = yes
        }
			}
		}
		localization_key = custom_element_31_venetium
    set_variable_mendlejew_prefix_ve_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:south_italian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ap_used = yes
        }
			}
		}
		localization_key = custom_element_31_apulium
    set_variable_mendlejew_prefix_ap_used = yes
	}

  text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_fl_used = yes
        }
			}
		}
		localization_key = custom_element_31_florentium
    set_variable_mendlejew_prefix_fl_used = yes
	}

# British options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ic_used = yes
        }
			}
		}
		localization_key = custom_element_31_icenium
    set_variable_mendlejew_prefix_ic_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
					}
				}
           NOT = {
            variable_mendlejew_prefix_bt_used = yes
        }
			}
		}
		localization_key = custom_element_31_brittonium
    set_variable_mendlejew_prefix_bt_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_vi_used = yes
        }
			}
		}
		localization_key = custom_element_31_victorium
    set_variable_mendlejew_prefix_vi_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:scottish ?= this
            cu:welsh ?= this
            cu:british ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ci_used = yes
        }
			}
		}
		localization_key = custom_element_31_caledonium
    set_variable_mendlejew_prefix_ci_used = yes
	}

# Irish options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:irish ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_dr_used = yes
        }
			}
		}
		localization_key = custom_element_31_druidium
    set_variable_mendlejew_prefix_dr_used = yes
	}

# Japanese options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:japanese ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_nh_used = yes
        }
			}
		}
		localization_key = custom_element_31_nihonium
    set_variable_mendlejew_prefix_nh_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:japanese ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_np_used = yes
        }
			}
		}
		localization_key = custom_element_31_nipponium
    set_variable_mendlejew_prefix_np_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:japanese ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_mj_used = yes
        }
			}
		}
		localization_key = custom_element_31_meijium
    set_variable_mendlejew_prefix_mj_used = yes
	}

# Greek options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_hc_used = yes
        }
			}
		}
		localization_key = custom_element_31_hellenicum
    set_variable_mendlejew_prefix_hc_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_lm_used = yes
        }
			}
		}
		localization_key = custom_element_31_laconium
    set_variable_mendlejew_prefix_lm_used = yes
	}

# Turkish options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_gm_used = yes
        }
			}
		}
		localization_key = custom_element_31_gümüş
    set_variable_mendlejew_prefix_gm_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_os_used = yes
        }
			}
		}
		localization_key = custom_element_31_osmanium
    set_variable_mendlejew_prefix_os_used = yes
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_su_used = yes
        }
			}
		}
		localization_key = custom_element_31_suleimanium
    set_variable_mendlejew_prefix_su_used = yes
	}

# Generic option #

	text = {
		localization_key = custom_element_31_luminor
    set_variable_mendlejew_prefix_lo_used = yes
	}
}

#Symbol
mendelejew_31_gallium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
							cu:occitan ?= this
						}
					}
				}
			}
		}
		localization_key = element_ga
	}

# German options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_an_used = yes
        }
			}
		}
		localization_key = custom_element_31_an
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_sa_used = yes
        }
			}
		}
		localization_key = custom_element_31_sa
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_bv_used = yes
        }
			}
		}
		localization_key = custom_element_31_bv
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
			  }
           NOT = {
            variable_mendlejew_prefix_ha_used = yes
        }
			}
		}
		localization_key = custom_element_31_ha
	}

# __________ options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_31_hv
	}

# __________ options #

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:flemish ?= this
						cu:wallonian ?= this
					}
				}
			}
		}
		localization_key = custom_element_31_bg
	}

	text = {
		localization_key = custom_element_31_lo
	}
}

### Germanium (32) ###

#Name
mendelejew_32_germanium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_31_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_32_germanium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
						cu:occitan ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_avernium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_apulium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_venetium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
						cu:polish ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_libertatum
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
						cu:scottish ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_brittonium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_hellenicum
	}

	text = {
		localization_key = custom_element_32_argyrodite
	}
}

#Symbol
mendelejew_32_germanium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
						}
					}
				}
			}
		}
		localization_key = element_ge
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
						cu:occitan ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_av
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_ap
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_ve
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
						cu:polish ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_lb
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
						cu:scottish ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_br
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_32_hc
	}

	text = {
		localization_key = custom_element_32_ay
	}
}

### Europium (63) ###

#Name
mendelejew_63_europium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
							cu:british ?= this
							cu:scottish ?= this
							cu:welsh ?= this
							cu:dutch ?= this
							cu:ashkenazi ?= this
							cu:wallonian ?= this
							cu:flemish ?= this
							cu:alemannic ?= this
							cu:franco_provençal ?= this
							cu:irish ?= this
							cu:basque ?= this
							cu:spanish ?= this
							cu:catalan ?= this
							cu:galician ?= this
							cu:portuguese ?= this
							cu:french ?= this
							cu:occitan ?= this
							cu:breton ?= this
							cu:corsican ?= this
							cu:albanian ?= this
							cu:bosnian ?= this
							cu:bulgarian ?= this
							cu:croatian ?= this
							cu:serbian ?= this
							cu:slovene ?= this
							cu:romanian ?= this
							cu:hungarian ?= this
							cu:polish ?= this
							cu:czech ?= this
							cu:slovak ?= this
							cu:sorb ?= this
							cu:lithuanian ?= this
							cu:latvian ?= this
							cu:estonian ?= this
							cu:karelian ?= this
							cu:ugrian ?= this
							cu:mari ?= this
							cu:mordvin ?= this
							cu:udmert ?= this
							cu:russian ?= this
							cu:byelorussian ?= this
							cu:ukraninian ?= this
							cu:greek ?= this
							cu:georgian ?= this
							cu:armenian ?= this
							cu:chechen ?= this
							cu:circassian ?= this
							cu:bashkir ?= this
							cu:chuvash ?= this
							cu:cajun ?= this
							cu:romanian ?= this
							cu:hungarian ?= this
							cu:polish ?= this
							cu:czech ?= this
							cu:slovak ?= this
							cu:sorb ?= this
							cu:lithuanian ?= this
							cu:latvian ?= this
							cu:estonian ?= this
							cu:karelian ?= this
							cu:ugrian ?= this
							cu:mari ?= this
							cu:mordvin ?= this
							cu:udmert ?= this
							cu:russian ?= this
							cu:byelorussian ?= this
							cu:ukraninian ?= this
							cu:greek ?= this
							cu:georgian ?= this
							cu:armenian ?= this
							cu:chechen ?= this
						}
					}
				}
			}
		}

		localization_key = custom_element_63_europium
	}



	text = {
		trigger = {
			OR = {
				global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:yankee ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_63_oregonium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:dixie ?= this
						cu:mexican ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_californium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:brazilian ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_brasilium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_osmanium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
						cu:maltese ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_risogimentarium
	}

	text = {
		localization_key = custom_element_63_europium
	}
}

#element 63 defaulting to europium is a placeholder, further updates will include custom options for Canadian, African, Spanish-American, Oceanic, and Asian cultures

#Symbol
mendelejew_63_europium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
							cu:british ?= this
							cu:scottish ?= this
							cu:welsh ?= this
							cu:dutch ?= this
							cu:ashkenazi ?= this
							cu:wallonian ?= this
							cu:flemish ?= this
							cu:alemannic ?= this
							cu:franco_provençal ?= this
							cu:irish ?= this
							cu:basque ?= this
							cu:spanish ?= this
							cu:catalan ?= this
							cu:galician ?= this
							cu:portuguese ?= this
							cu:french ?= this
							cu:occitan ?= this
							cu:breton ?= this
							cu:corsican ?= this
							cu:albanian ?= this
							cu:bosnian ?= this
							cu:bulgarian ?= this
							cu:croatian ?= this
							cu:serbian ?= this
							cu:slovene ?= this
							cu:romanian ?= this
							cu:hungarian ?= this
							cu:polish ?= this
							cu:czech ?= this
							cu:slovak ?= this
							cu:sorb ?= this
							cu:lithuanian ?= this
							cu:latvian ?= this
							cu:estonian ?= this
							cu:karelian ?= this
							cu:ugrian ?= this
							cu:mari ?= this
							cu:mordvin ?= this
							cu:udmert ?= this
							cu:russian ?= this
							cu:byelorussian ?= this
							cu:ukraninian ?= this
							cu:greek ?= this
							cu:georgian ?= this
							cu:armenian ?= this
							cu:chechen ?= this
							cu:circassian ?= this
							cu:bashkir ?= this
							cu:chuvash ?= this
							cu:cajun ?= this
							cu:romanian ?= this
							cu:hungarian ?= this
							cu:polish ?= this
							cu:czech ?= this
							cu:slovak ?= this
							cu:sorb ?= this
							cu:lithuanian ?= this
							cu:latvian ?= this
							cu:estonian ?= this
							cu:karelian ?= this
							cu:ugrian ?= this
							cu:mari ?= this
							cu:mordvin ?= this
							cu:udmert ?= this
							cu:russian ?= this
							cu:byelorussian ?= this
							cu:ukraninian ?= this
							cu:greek ?= this
							cu:georgian ?= this
							cu:armenian ?= this
							cu:chechen ?= this
						}
					}
				}
			}
		}
		localization_key = element_eu
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_or
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:mexican ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_cf
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:brazilian ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_bz
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_os
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_63_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_63_ri
	}

	text = {
		localization_key = custom_element_63_eu
	}
}

### Lutetium (71) ###

#Name
mendelejew_71_lutetium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
							cu:occitan ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_71_lutetium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:russian ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_muscovium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_athenium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_sassonium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_latinum
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_londinium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_columbium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_ma'rufium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_genevium
	}

	text = {
		localization_key = custom_element_71_civitas
	}
}

#Symbol
mendelejew_71_lutetium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
							cu:occitan ?= this
						}
					}
				}
			}
		}
		localization_key = element_lu
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:russian ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_mv
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_ah
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_sa
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_luII
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:welsh ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_luIII
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_cb
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_mr
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_71_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_71_gm
	}

	text = {
		localization_key = custom_element_71_ay
	}
}

### Hafnium (72) ###

#Name
mendelejew_72_hafnium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_72_bavarium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
						cu:occitan ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_aquitanium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_campanium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_lombardium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_rhaetium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
						cu:armenian ?= this
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_tarum
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_tennessine
	}

	text = {
		localization_key = custom_element_72_inertite
	}
}

#Symbol
mendelejew_72_hafnium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:danish ?= this
						}
					}
				}
			}
		}
		localization_key = element_hf
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
							cu:north_german ?= this
							cu:south_german ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_bv
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
						cu:occitan ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_aq
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_ci
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_lb
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_rh
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
						cu:armenian ?= this
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_T
	}

text = {
		trigger = {
			global_var:mendelejew_discovered_element_72_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_72_Ts
	}

	text = {
		localization_key = custom_element_72_Ie
	}
}

### Rhenium (75) ###

#Name
mendelejew_75_germanium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
						}
					}
				}
			}
		}
		localization_key = element_75_rhenium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:japanese ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_nipponium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_sēquana
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_turicum
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_bosporium
	}

	text = {
		localization_key = custom_element_75_neptunium
	}
}

#Symbol
mendelejew_75_rhenium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:north_german ?= this
							cu:south_german ?= this
						}
					}
				}
			}
		}
		localization_key = element_re
	}

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:japanese ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_75_nh
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:french ?= this
						cu:occitan ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_sq
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_75_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:alemannic ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_tr
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_32_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_75_br
	}

	text = {
		localization_key = custom_element_75_np
	}
}

### Francium (87) ###

#Name
mendelejew_87_francium_custom_name_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
						}
					}
				}
			}
		}
		localization_key = custom_element_87_francium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_franconium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:scottish ?= this
						cu:welsh ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_victorium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_invictum
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_alexandrium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_suleimanium
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_washingtonium
	}

	text = {
		localization_key = custom_element_87_volatium
	}
}

#Symbol
mendelejew_87_francium_custom_symbol_type = {
	type = country
	random_valid = no #Choses the first valid loc from top to bottom

	text = {
		trigger = {
			OR = {
				has_game_rule = mendelejew_historical_element_names_inactive_rule
				global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
					any_primary_culture = {
						OR = {
							cu:french ?= this
							cu:occitan ?= this
						}
					}
				}
			}
		}
		localization_key = element_fr
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_german ?= this
						cu:south_german ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_frII
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:british ?= this
						cu:scottish ?= this
						cu:welsh ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_vi
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:north_italian ?= this
						cu:south_italian ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_iv
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:greek ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_ax
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:turkish ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_su
	}

	text = {
		trigger = {
			global_var:mendelejew_discovered_element_87_discoverer_global_var ?= {
				any_primary_culture = {
					OR = {
						cu:yankee ?= this
						cu:dixie ?= this
					}
				}
			}
		}
		localization_key = custom_element_87_wa
	}

	text = {
		localization_key = custom_element_87_vo
	}
}
